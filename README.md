For this web scraping project, we perform two different tasks: one involves scraping data from a webpage, and the other focuses on scraping a table from Wikipedia.

Web Scraping Data from a Webpage (Web Scraping Data from Web.ipynb):
We use the requests library to send a GET request and retrieve the HTML content from the Taiwanese water tracking webpage (https://water.taiwanstat.com/). Using BeautifulSoup, we parse the HTML and extract the specific water data we need from the webpage.

![image](https://github.com/user-attachments/assets/1ec7fd68-7caa-4266-bf18-cb33ffc0cb1d)

Web Scraping a Table from Wikipedia (Web Scraping Table from Wikipedia.ipynb):
We use the requests library to retrieve the HTML from the Wikipedia page (https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue). Then, using BeautifulSoup, along with the find_all method and a for loop, we extract the relevant table data. We process this data and convert it into a Pandas DataFrame for further analysis.

![image](https://github.com/user-attachments/assets/21672850-c169-4d74-bba7-058343dfe9d2)
