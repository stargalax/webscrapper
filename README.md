# Flask Image Scraper

A simple Flask application that scrapes images from a specified URL, allows users to ignore certain images based on predefined keywords, and provides the option to download the images in a zip file.

## Features

- Scrapes all images from a given webpage.
- Allows users to specify additional keywords to ignore.
- Provides a downloadable zip file containing the scraped images.
- Option to create a separate zip file for ignored images.

## Requirements

- Python 3.x
- Flask
- Requests
- BeautifulSoup4

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/flask-image-scraper.git
   cd flask-image-scraper

**Install the libraries**
pip install Flask requests beautifulsoup4

**Run the application**
python app.py

Open your web browser and go to the website that the code gives (a local server)

**Usage**
Enter the URL of the webpage you want to scrape in the input field.
Optionally, enter keywords (one per line) that you want to ignore while scraping images.
Click the "Scrape" button.
The application will display the images that were ignored and provide a link to download the zip file of valid images.
You can also select ignored images and create a zip file for them.

**Error Handling**
If no images are found on the specified URL, the application will notify the user.
If the URL is invalid or an error occurs during scraping, an error message will be displayed.

the website still needs a lot of work to be done! just wanted to add this to track my progress! (┬┬﹏┬┬)
