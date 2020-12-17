# Data-Gathering-and-scraping
## 1. Data scraping

We all love watching movies, don't we? In this part of the homework you will learn how to scrape the popular movie review site, IMDB, by extracting information from it and learning more about some of the most popular movies.

Data Gathering: Scrape data about the TOP 250 IMDB movies: (Links to an external site.)
Note: The above link has just 100 movies, you need to scrape 3 pages to get all the 250 movies.

Use BeautifulSoup4 Library to scrape the above link.
Extract and store the Movie Name, Year, Rating, Genre, Director, & Number of Votes, (check the below image) in the format of your liking. (If a movie has multiple genres and/or directors, store the first one)
Rating here means the star rating and not the Metascore. 
Matrix.png

### Analysis:

Which movie received the most and which the least votes?
Generate a Bar plot of Genre vs. Movie Count. Which Genre has the most movies?
Find the Top 5 Directors with the most number of movies in the Top 250 List.

## 2. 2. Database access

Through Google BigQuery, Google provides commercial access to one of the largest data repositories in the world, collected from thousands of sources. Many are of public interest, and some are available free. One of those is weather data from NOAA. The US National Oceanic and Atmospheric Administration (NOAA) tracks the weather in the US and publishes the data regularly. The data is split into datasets on temperature, air quality, storm occurence, etc. Here you will gather NOAA data about severe storms in the USA.

Data Gathering: Gather the data on historic severe storms from the noaa_historic_severe_storms from Google BigQuery. Use an SQL query through pandas-gbq (Links to an external site.) to get a pandas data frame for the analysis.

Before you begin, a) Make sure your account is in SANDBOX (Links to an external site.) mode, such that you do not need to register with your credit card and it is free, and b) Create a Cloud Platform project if you do not already have one. The query will be run under the project_id you specify (the default project Name is 'My First Project', but you will need to find out the ID instead of the Name).

### Analysis: 

What are the 40 most frequent storm event types between years 1950 and 2000? What is the top event type?
Generate a Bar Plot of tornados over each of the five decades, 1950s, 1960s, 1970s, 1980s, and 1990s.

## 3. File download: 

The US presidential election is upon us. While waiting for the actual voting and results, there is an established way to quantitatively forecast who will win the two-way race for president. The forecasting uses polling data (i.e., polls). Polling is conducted by asking random people, at different times before the election, who they would vote for. There are tens of different credible pollsters out there, who all conduct polls regularly and publish their poll results publicly. Here you will gather data of all 2020 polls.

Data Gathering: The site http://fivethirtyeight.com/  (Links to an external site.) is famous for running statistical models predicting presidential outcomes from polls, but they also run models about many other things, like NBA scores etc. To complete this part you'll have to download the Latest polls data from https://data.fivethirtyeight.com/ (Links to an external site.), specifically the 2020 presidential primary polls, president_primary_polls.csv (click on the blue circle with a white arrow).

### Analysis: Once you gather the data, calculate the following:

How many unique presidential candidates were on the ballots overall?
What was the average sample size in the national polls in 2020?
