# Airbnb Kaggle Competition: New User Bookings

This repository contains materials for the MSCA 31008 Data Mining Principles Team Project at the University of Chicago.

:earth_americas: Where will the next AirBnB user book their first travel experience?

Code developed for [AirBnB's Kaggle competition](https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings/overview). The XGBOOST code gives a score of around 0.88173 on the public leaderboard.

## Team: 

![](https://i.ibb.co/8Nydpjh/Team.png)

_Chris Reimann [creimann@uchicago.edu](creimann@uchicago.edu)_

_Devanshi Verma [devanshi@uchicago.edu](devanshi@uchicago.edu)_

Professor: Dr. Anil Chaturvedi


## Description

New users on Airbnb can book a place to stay in 34,000+ cities across 190+ countries. By accurately predicting where a new user will book their first travel experience, Airbnb can share more personalized content with their community, decrease the average time to first booking, and better forecast demand.

## Data

As per competition rules, we cannot share the dataset. But feel free to have a look at [Competition Data](https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings/data). 

This dataset revolves around predicting where (country) a new user will book their first travel experience. The data is composed of demographics, web session records, and some summary statistics of the users from the United States. There are 12 possible outcomes of the destination country: 'US', 'FR', 'CA', 'GB', 'ES', 'IT', 'PT', 'NL','DE', 'AU', 'NDF' (no destination found), and 'other'. AirBnB provides us with 6 datasets. Train users, Test users, web sessions, country, age buckets, and a sample submission CSV file.

## Structure of the repository

- Code Folder: This folder contains the main python notebook which covers our main code. It also contains code for the evaluation metric used for the kaggle competition.

- Output: This contains our submission.

## Structure of the code
1.1 Importing the files and loading the dataset
1.2 EDA
1.3 Feature Engineering
1.4 Evalutation Metric by Kaggle
1.5 Understanding what makes a new user books a place
1.6 Models
	1.6.1 Decision Tree
	1.6.2 Logistic Regression
	1.6.3 Random Forest
	1.6.4 KNN
	1.6.5 XGBOOST
	1.6.6 Ensemble Model
1.7 Preparing data for submission
1.8 Future Work







