# Lab 3 – Web Scraping Weather Data
### Summary of Lab
In this lab, we edited a web scraping code that identified the current weather conditions for a given latitude and longitude (I chose Arlington, Virginia). This code uses the `BeautifulSoup` function to parse through the html of the website and find the `id` values that are given when you inspect an element on the web page. 


### Errors? 
When I edited the code with new coordinates and added the extra lines to scrape the detailed weather conditions, I originally got an error that the line that extracted the text had an Attribute Error, although I hadn't edited that portion of the code. After rereading through my code, I found that I had made a misake where I had inputted the new coordinates, and this was the actual source of the error. After fixing this, the code ran fine. 

