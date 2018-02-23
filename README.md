# Zillow Real Estate Listing Scraper

This script will scrape Zillow.com, an online real estate database to extract real estate listings available based on a zip code.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

For this web scraping tutorial using Python 3, we will need some packages for downloading and parsing the HTML. 
Below are the package requirements:

 - lxml
 - requests

### Installation

PIP to install the following packages in Python (https://pip.pypa.io/en/stable/installing/).

Python Requests, to make requests and download the HTML content of the pages (http://docs.python-requests.org/en/master/user/install/).

To install python request module:

```
pip3 install requests
```

Python LXML, for parsing the HTML Tree Structure using Xpaths (Learn how to install that here – http://lxml.de/installation.html)
Installing lxml:

```
pip3 install lxml
```

Python Requests, to make requests and download the HTML content of the pages (http://docs.python-requests.org/en/master/user/install/).

## Running the scraper
You must run the script using python with arguments for zip code and sort. The sort argument has the options ‘newest’ and ‘cheapest’
listings available. As an example, to find the listings of the newest properties up for sale in Boston, Massachusettswe would run the 
script as:

```
python3 zillow.py 02126 newest
```
## Sample Output

This will create a csv file:

 [Sample Output]
 
 
