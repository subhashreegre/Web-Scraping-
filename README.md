# Web-Scraping using BeautifulSoup
Developed a tool to extract data from website https://books.toscrape.com/ using Python & BeautifulSoup. 
The extracted data can be stored in a .csv file (uploaded here).

## Guidelines:
Web scraping is a technique to extract data from websites.

### Prerequisites
Before you start, make sure you have the following installed:
- Python 3.x
- Requests library
- Beautifulsoup4 library
  
You can install the required libraries using pip: pip install requests beautifulsoup4 
## Step 1: 
- Import Libraries: First, import the necessary libraries.
## Step 2:
- Import requests:  from bs4 import BeautifulSoup
## Step 3: 
- Parse the HTML content of the page using BeautifulSoup: bs = BeautifulSoup(response.content, 'html.parser')
## Step 4: 
- Extract the Data: Now, you can extract the data you need. For example, to extract all the headings(h1) tags from the page:
- headings = soup.find_all('h1')
- for heading in headings:
    print(heading.text)
## Step 5:
- Handling Errors : Always make sure to handle errors, such as connection issues or pages not found.
## Step 6:
Putting It All Together
Here's a complete example that scrapes the headings, links, and paragraphs from a webpage

## Conclusion
This README.md file provides a basic introduction to web scraping using BeautifulSoup and Python. 

## Happy scraping!!!





### Developed by Subhashree Roy.
