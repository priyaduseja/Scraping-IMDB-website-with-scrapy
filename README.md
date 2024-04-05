# Scraping-IMDB-website-with-scrapy

## IMDb Movies Data Scraping

**Overview**
This project comprises two Python scripts that scrape data from IMDb's list of top-rated movies and extract various details such as movie names, release years, durations, and genres.

**Code Description**

**Script 1: IMDb Movie Duration**

1. **Description:** This script scrapes IMDb's list of top-rated movies and extracts movie names, durations, and genres.
2. **Implementation:** It defines a Scrapy spider named IMDB_Movie and specifies the starting URL as IMDb's list of top-rated movies.
The spider extracts movie names and URLs from the initial page and follows each movie URL to extract additional information such as duration and genres.
The extracted data is then saved into a CSV file named IMDB_Movies_Duration.csv.

**Script 2: IMDb Movie Year and Release Date**
1. **Description:** This script scrapes IMDb's list of top-rated movies and extracts movie names, release years, and release dates.
2. **Implementation:** It defines another Scrapy spider named Movies with the same starting URL as IMDb's list of top-rated movies.
Similar to the first script, it extracts movie names, release years, and URLs from the initial page and follows each movie URL to extract release dates.
The extracted data is saved into a CSV file named IMDB_Movies_Year_ReleaseDate.csv.

**Dependencies**
Python 3, Scrapy

**Usage**
Clone the repository to your local machine.
Install the required dependencies using pip.
Run each script individually to scrape the desired data.
The scraped data will be saved into respective CSV files within the project directory.
