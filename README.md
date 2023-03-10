# data-collection-coding
## web scraping and data analysis
This project consists of two technical products.
 1: Scrape titles and preview text from Mars news articles.
 2: Scrape and analyze Mars weather data, which exists in a table.

## Part 1: Scrape Titles and Preview Text from Mars News

Use automated browsing to visit the Mars news site. Inspect the page to identify which elements to scrape.

Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures 

Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. 
Print the list in your notebook.

## Part 2: Scrape and Analyze Mars Weather Data

Use automated browsing to visit the Mars Temperature Data Site. 

Inspect the page to identify which elements to scrape. The URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.

Create a Beautiful Soup object and use it to scrape the data in the HTML table.

Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. 

Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.

How many months exist on Mars?

How many Martian (and not Earth) days worth of data exist in the scraped dataset?

What are the coldest and the warmest months on Mars (at the location of Curiosity)? 

Which months have the lowest and the highest atmospheric pressure on Mars? 

About how many terrestrial (Earth) days exist in a Martian year? 

Export the DataFrame to a CSV file.

### Analysis

![image](https://user-images.githubusercontent.com/120197958/224377926-ecf8e992-7d54-4fc6-ac7d-51ffe22f590f.png)

On average, the third month has the coldest minimum temperature on Mars, and the eighth month is the warmest. But it is always very cold there in human terms!

![image](https://user-images.githubusercontent.com/120197958/224378089-5037282b-986b-4b84-b29e-904a4112ab81.png)

Atmospheric pressure is, on average, lowest in the sixth month and highest in the ninth.

![image](https://user-images.githubusercontent.com/120197958/224378210-fba0f063-193f-4c4a-83ee-3e9142b42f3d.png)

The distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms that a Mars year is equivalent to 687 earth days.
