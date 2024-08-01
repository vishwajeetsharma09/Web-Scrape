# HPRERA Project Scraper

This Python script scrapes the first 6 registered projects listed on the [HPRERA Public Dashboard](https://hprera.nic.in/PublicDashboard) and extracts detailed information including GSTIN No, PAN No, Name, and Permanent Address.

## Requirements

To run this script, you need to have Python 3 installed on your machine. Additionally, you need to install the following Python packages:

- `requests`
- `beautifulsoup4`

You can install these packages using pip:

```bash
pip install requests beautifulsoup4
```
Usage
Clone this repository or download the script file.
Ensure you have the required packages installed.
Run the script:
python file name .py

The script will print the details of the first 6 registered projects to the console.

Script Overview
The script performs the following steps:

Sends a GET request to the HPRERA Public Dashboard to fetch the HTML content.
Parses the HTML content using BeautifulSoup.
Locates the "Registered Projects" section and finds the links to the first 6 project detail pages.
Visits each project detail page and extracts the required information (GSTIN No, PAN No, Name, and Permanent Address).
Prints the extracted information to the console.

Sample Output
The output of the script will look like this:
```bash
Project 1:
  GSTIN No: XXXXXXX
  PAN No: XXXXXXX
  Name: Project Name 1
  Permanent Address: Address 1

Project 2:
  GSTIN No: XXXXXXX
  PAN No: XXXXXXX
  Name: Project Name 2
  Permanent Address: Address 2

...
```

