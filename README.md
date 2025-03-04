# Last.fm Rankings Scraper

This repository contains a Jupyter Notebook that scrapes user ranking data from Last.fm. The script automates web browsing using Selenium and extracts relevant ranking data using BeautifulSoup.

## Features
- Uses Selenium WebDriver to navigate Last.fm user library pages.
- Extracts and processes ranking data for a given year.
- Supports environment variable configuration for driver path.

## Requirements
Ensure you have the following dependencies installed:

```bash
pip install selenium beautifulsoup4 pandas python-dotenv
```

Additionally, download the appropriate version of the Chrome WebDriver:
[Chrome for Testing](https://googlechromelabs.github.io/chrome-for-testing/)

## Usage
1. Configure the `.env` file to include:
   ```plaintext
   CHROMEDRIVER_PATH=<path_to_chromedriver>
   ```
2. Update the `user_name` and `year` variables in the notebook.
3. Run the notebook to initiate scraping.

## Notes
- Ensure you have the correct version of Chrome installed to match the WebDriver.
- The script accepts cookies automatically when navigating to the Last.fm user page.

## License
This project is open-source. Check the repository for licensing details.