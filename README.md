# Walmart Store Locator
Walmart.com Store Locator Web Scraper written in Pythoon to extract store locations available based on a zip code.
If you would like to know more about this scraper you can check it out at the blog post 'How to Scrape Store Locations using Python' - 

## Getting Started
These instruction will get you a copy of the project up and running on your local machine for development and testing purposes.

### Fields to Extract
This walmart scraper can extract the following fields below:
1. Store Name
2. Store ID
3. Distance (in miles) from a given zip code
4. Address
5. Zip Code
6. City
7. Phone Number

### Prerequisites
For this web scraping tutorial usng Python 3, we will need some some packages:
* Python requests
* UnicodeCSV

### Installation
PIP to install the following packages in Python (https://pip.pypa.io/en/stable/installing/)

Python Requests, to make requests and download the HTML content of the pages (http://docs.python-requests.org/en/master/user/install/)

Python LXML, for parsing the HTML Tree Structure using Xpaths (Learn how to install that here – http://lxml.de/installation.html)

## Running the Scraper
We will execute the code with the script name followed by the arugument for zip code. here is an example to find the store locations and
its details in Boston, MA
///
python3 walmart_store_retreiver 20005
///

## Sample Output
This will create a CSV file:
[Sample Output](https://raw.githubusercontent.com/scrapehero/walmart_store_locator/master/20005_stores.csv)
