
# Seattle AirBnB prices 
This project analyzes the Seattle AirBnB property prices and sentiments of reviews about these properties.
We also build a machine learning model to predict property prices using Linear Regression.

## Libraries used in the Analysis
- pandas
- numpy
- sklearn
- os 
- datetime
- matplotlib
- seaborn
- wordcloud

## Input Data
Folder Structure of Repository:

|
|___AirBnB Data.ipynb
|___Seattle
	|___Listings.csv
	|___Calendars.csv
	|___Reviews.csv

The datasets are 3 csv files listed in the folder "Seattle"
Listings is a dataset which has a bunch of features of each property and price. This dataset is unique at Listing_id level.
Calendar is a dataset which has information at day level whether a property is available or occupied, and the price if available
Reviews has customer feedback and comments for each property along with date

## Business Questions
In the notebook we will try to answer the below questions
1. How are property prices distributed in Seattle ?
2. Build a model to predict price based on important independent variables from the data
3. What are consumers talking about AirBnB Seattle

## Summary
In the notebook, we analyze the distribution of price and find the cheapest and the most expensive regions to stay
We built a linear regression model to predict price in this study with an R2 metric of 0.64
Also, we visualized the top keywords from comments about these properties building a wordcloud

## Acknowledgements
The data is procured from Kaggle and can be downloaded from the below link https://www.kaggle.com/airbnb/seattle/data
