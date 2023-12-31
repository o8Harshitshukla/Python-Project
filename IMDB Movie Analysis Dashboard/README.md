# IMDB Movie Analysis

## Business Problem

IMDB, the world's largest movie rating platform, plays a crucial role in influencing viewers' movie choices. Many users rely on IMDB ratings, the number of votes, and reviews to decide which movies to watch. The data collected by IMDB is invaluable for understanding public preferences, identifying profitable movie genres, and predicting movie revenue.

The goal of this project is to explore and analyze the IMDB dataset to generate insights that can drive revenue in the movie industry. By examining ratings, revenue, genres, and other factors, we aim to answer questions like which genres are most profitable, which genres receive high ratings but lower revenue, and how ratings impact a movie's success.

## Data Description

The dataset contains information from IMDB, including movie titles, ratings, revenue, release year, and more. This data is essential for studying the relationship between ratings and revenue and uncovering correlations between movie genres, ratings, and earnings.

### Data Dictionary

![image](https://github.com/Nasir151/Python-Projects/assets/94509995/81da7daf-c038-4ce4-b860-ad5057095c38)

-----------------------------------------------------------------------------------------------------------------
#### Question 1: How many rows are there in the IMDB dataset?

![Capture](https://github.com/Nasir151/Python-Projects/assets/94509995/73756c37-79ca-4be3-8738-ccca85faa45e)

#### Question 2: What is the 75th percentile of rating in the IMDB dataset?

![Capture](https://github.com/Nasir151/Python-Projects/assets/94509995/29ab66b3-b4f1-4147-86fa-3d16483dd0d0)

#### Question 3: How many NA values are there in the field ‘Revenue’?

![Capture](https://github.com/Nasir151/Python-Projects/assets/94509995/54c8a1d2-e6d0-42a5-a59b-a10fd5a19079)

#### Question 4: How many movies have revenue higher than 75 million?

![Capture](https://github.com/Nasir151/Python-Projects/assets/94509995/7685257c-1c27-4eb9-90a6-d2dfc016c59d)

#### Question 5: How many movies have revenue greater than 50 million but rating less than 7?

![Capture](https://github.com/Nasir151/Python-Projects/assets/94509995/6eb97a22-bace-48f7-8cc6-20e32a3e4e1f)

#### Question 6: What is the total revenue generated by movies in the year 2015?

![Capture](https://github.com/Nasir151/Python-Projects/assets/94509995/3ad165e6-d251-4cae-92d0-72ab6948a53e)

#### Question 7: What is the average rating for the genre adventure in the year 2015?

![Capture](https://github.com/Nasir151/Python-Projects/assets/94509995/261d0415-4650-43b2-94da-cc9607d25981)

#### Question 8: What is the average duration of movies in rows 75 to 150? Please note that the rows in python start from 0.

![Capture](https://github.com/Nasir151/Python-Projects/assets/94509995/99684c91-dd90-4141-9e70-dee9dbafa58b)

#### Question 9: Which year generated the highest revenue?

![Capture](https://github.com/Nasir151/Python-Projects/assets/94509995/70cfe077-a13f-4fbb-a083-9b9194a2d1da)

#### Question 10: What is the maximum revenue out of (10,20,30,40,50) rows?

![Capture](https://github.com/Nasir151/Python-Projects/assets/94509995/39c2b639-1c54-4c53-a65a-5d152d33f8d1)

#### Question 11: How many movies with the genres ‘Adventure’, ‘Action’, ‘Horror’, and ‘Crime’ exist in the IMDB dataset?

![Capture](https://github.com/Nasir151/Python-Projects/assets/94509995/4f188972-6720-40ba-92a0-bc1f61a7a2ce)

#### Question 12: Create a genre-level report with metrics average rating, the average number of votes, and average revenue. What is the average rating of the ‘Horror’ genre? (Round to 2 decimal places)

![Capture](https://github.com/Nasir151/Python-Projects/assets/94509995/d39c77a1-a830-4919-90f5-1d55d54a8e00)

#### Question 13: Create a report to showcase the revenue of each movie, as % revenue concerning the total revenue of the respective genre and year of the movie.

    Note: Percentage = Revenue of movie * 100 / (Total revenue of genre and year)

![Capture](https://github.com/Nasir151/Python-Projects/assets/94509995/16a305ae-89c5-4b15-b01b-de73781450bf)

![image](https://github.com/Nasir151/Python-Projects/assets/94509995/ef4a489c-467a-453f-ad39-3303482b8555)

![Capture](https://github.com/Nasir151/Python-Projects/assets/94509995/6fe841ca-883f-4f47-9634-f543f84368e5)

![Capture](https://github.com/Nasir151/Python-Projects/assets/94509995/88c9d812-9008-47e3-bd97-43adf0212174)

#### Question 14: What is the average ‘Votes_norm’ ? (Round to two decimal places)
    Note: Votes_norm = [Votes - min(Votes)]*10/[max(votes) - min(votes)

![Capture](https://github.com/Nasir151/Python-Projects/assets/94509995/ebca2858-54f5-456c-a34f-f45ccf486b9e)

#### Question 15: What is the highest ‘Total_rating’?

    Note: Total_rating is ‘Rating’+ ‘Votes_norm’

![Capture](https://github.com/Nasir151/Python-Projects/assets/94509995/0256a608-f818-42a1-b5d3-0c112328978a)

#### Question 16: Create a new column ‘Revenue_bins’ so that ‘Revenue_millions’ are categorized in buckets 0-50, 51-100, 101-150, and 150+. Which bucket has the highest number of movies?

![Capture](https://github.com/Nasir151/Python-Projects/assets/94509995/45c72b60-f993-4a3d-bc8f-09fa00d07489)

![Capture](https://github.com/Nasir151/Python-Projects/assets/94509995/fcae7cc2-7ad9-4591-a0b3-35fd30d713ed)

#### Question 17: How many directors have created movies in the highest number of genres?

![Capture](https://github.com/Nasir151/Python-Projects/assets/94509995/915b308e-e199-44fd-89c9-16359dccb095)

![Capture](https://github.com/Nasir151/Python-Projects/assets/94509995/707f17bd-3637-43c6-a122-981f1df7d08f)
