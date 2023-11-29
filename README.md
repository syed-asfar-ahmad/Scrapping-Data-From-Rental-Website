# Scrapping-Data-From-Rental-Website

This Python script uses BeautifulSoup and requests libraries to scrape apartment listings from the Pararius website in Amsterdam.

## Requirements

- Python 3.x
- BeautifulSoup (`pip install beautifulsoup4`)
- Requests (`pip install requests`)
- lxml (`pip install lxml`)

## Usage

1. Clone the repository or download the `scraper.py` file.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the `scraper.py` file.

```bash
python scraper.py

Script Overview
scraper.py: Python script for scraping apartment listings.
SlashByte Studios.csv: Output CSV file containing URLs, titles, and monthly prices of listings.
Notes
The script fetches apartment listing URLs from multiple pages on the Pararius website.
It then extracts specific information (title and price) for each listing URL.
The extracted data is stored in a CSV file named SlashByte Studios.csv.
