# Web-scraping Challenge
Web-scraping, BeautifulSoup, HTML, Pandas

## Background
You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.

## Part One - Scrape Titles and Preview Text from Mars News
found in file: Part_1_mars_news.ipynb

## Part Two - Scrape and Analyze Mars Weather Data
found in file: part_2_mars_weather.ipynb

### How many months exist on Mars?
according to our data the count of the months the rover spent on mars is broken down into the following:
![image](https://github.com/nicduffee/webscraping-challenge/assets/91498217/66678b29-cabe-4cfa-bad3-122402f4aefb)

However, according to NASA, Mars has twice as many months as Earth due to being further away from the sun. </br>
https://mars.nasa.gov/all-about-mars/facts/mars-year/

### How many Martian (and not Earth) days worth of data exist in the scraped dataset?
Their are 1867 Martian days worth of data in our dataset
![image](https://github.com/nicduffee/webscraping-challenge/assets/91498217/b7315f1b-7a0c-4192-bdd5-99b8f9c0c5c0)

### What are the coldest and the warmest months on Mars (at the location of Curiosity)?
The coldest month on average is the 3rd Month and the warmest month on average is the 8th Month as seen in the graphs below (second graph sorted to show coldest to warmest):

![Average_Low_Temp](https://github.com/nicduffee/webscraping-challenge/assets/91498217/1b9e197d-4b32-43f9-8408-0c4db7fec174)
![Sorted_Average_Low_Temp](https://github.com/nicduffee/webscraping-challenge/assets/91498217/ff055abd-e56a-47e3-9efb-962825731255)

### Which months have the lowest and the highest atmospheric pressure on Mars?
the 6th month has the lowest atmospheric pressure and the 9th month has the highest atmospheric pressure as seen in the below sorted graph:

![Sorted_Average_Pressure](https://github.com/nicduffee/webscraping-challenge/assets/91498217/e4654e40-79b6-4e1e-8e2c-4697604d2e45)

### About how many terrestrial (Earth) days exist in a Martian year?

![image](https://github.com/nicduffee/webscraping-challenge/assets/91498217/b4c1b7a5-7ef8-4478-acac-e43e3e3f78cf)

The distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms that a Mars year is equivalent to 687 earth days.






