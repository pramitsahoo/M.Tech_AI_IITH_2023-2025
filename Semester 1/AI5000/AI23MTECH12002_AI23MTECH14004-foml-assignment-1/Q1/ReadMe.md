# Meal Time Prediction - README
### Contributors: Pramit Sahoo (AI23MTECH14004) and Sunayna Padhye (AI23MTECH12002)
### Assignment 1 - AI5000 Foundations of Machine Learning - IIT Hyderabad

## Abstract
We investigate the performance of two time series forecasting models, Poisson regression and exponential regression, on the problem of predicting the time taken to finish food in the mess for breakfast, lunch, tea, and dinner for the next 2 weeks.<br>
We first prepare the data by considering various features like day, time, holiday, and category (breakfast, lunch, tea, dinner). We then perform an exploratory data analysis to understand the relationships between the features and the target variable.<br>
We then fit the Poisson and exponential regression models to the data using Maximum Likelihood estimation. We analyze the parameter values and compare the predictive performance of the two models on a held-out test set.<br>
We find that the Linear regression model outperforms the exponential regression and poisson regression model because of the small dataset. We also find that the most important features for predicting the time taken to finish food are the category of the meal and the time of day.<br>


Keywords: time series forecasting, Poisson regression, exponential regression, machine learning

.

## Repository Structure
The repository contains 7 files:
* 1 Jupyter notebook file - 1_FOML_Assignment_1.ipynb
* 1 Dataset file - dataset_data.csv
* 1 ReadMe file - ReadMe.md
* 1 Libraries file - requirements.txt

## Code Usage - (Python 3.10, conda 4.12)
1. Install required python libraries from requirements.txt <br>
(refer to https://medium.com/python-pandemonium/better-python-dependency-and-package-management-b5d8ea29dff1 for steps to install libraries using requirements.txt)
2. Download all Jupyter notebook and Dataset files into one directory.
3. Open Jupyter notebook into that directory.
4. Select the required notebook (.ipynb file) and select "Run All" inside the jupyter notebook file.
