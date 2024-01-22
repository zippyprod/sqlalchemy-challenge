# sqlalchemy-challenge
## Module 10 Challenge

## Instructions
Congratulations! You've decided to treat yourself to a long holiday vacation in Honolulu, Hawaii. To help with your trip planning, you decide to do a climate analysis about the area. The following sections outline the steps that you need to take to accomplish this task.

## Solutions files are contained in the main branch
app.py and the climate.ipynb

# Part 1: Analyze and Explore the Climate Data
In this section, you’ll use Python and SQLAlchemy to do a basic climate analysis and data exploration of your climate database. Specifically, you’ll use SQLAlchemy ORM queries, Pandas, and Matplotlib.

 ## Precipitation Analysis
  1. Find the most recent date in the dataset.

  2. Using that date, get the previous 12 months of precipitation data by querying the previous 12 months of data.
  3. Select only the "date" and "prcp" values.
  4. Load the query results into a Pandas DataFrame. Explicitly set the column names.
  5. Sort the DataFrame values by "date".
  6. Plot the results by using the DataFrame plot method, as the following image shows:
  7. Use Pandas to print the summary statistics for the precipitation data.

## Use Pandas to print the summary statistics for the precipitation data.

1. Design a query to calculate the total number of stations in the dataset.
2. Design a query to find the most-active stations (that is, the stations that have the most rows). To do so, complete the following steps:

  *  List the stations and observation counts in descending order.
  *  Answer the following question: which station id has the greatest number of observations?

3. Design a query that calculates the lowest, highest, and average temperatures that filters on the most-active station id found in the previous query.

  * Filter by the station that has the greatest number of observations.
  * Query the previous 12 months of TOBS data for that station.
  * Plot the results as a histogram with bins=12, as the following image shows:
  * Close the session

## Part 2: Design Your Climate App

Now that you’ve completed your initial analysis, you’ll design a Flask API based on the queries that you just developed. To do so, use Flask to create your routes.






