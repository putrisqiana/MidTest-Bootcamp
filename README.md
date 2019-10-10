# MidTest-Bootcamp

Case 1
Dataset : water.csv
Code : 

Background : The Dataset provides the annual water usage in Baltimore from 1885 to 1963, or 79 years of data.
The values are in the units of liters per capita per day, and there are 79 observations.

Objective : Create a python script for the Use Case below, please upload the script after you finish.
The Problem is to predict annual water usage.

Instructions :

Load the dataset as a Pandas Series and split into two, one for model development (dataset.csv) and the other for validation (validation.csv).
Create summary of the dataset, with python function.
Create A line plot of a time series dataset, it will provide a lot of insight into the problem.
Group the annual data by decade and get an idea of the spread of observations for each decade and how this may be changing.
Create models using ARIMA
Split the dataset into train and test sets directly
The first 50% of the dataset will be held back to train the model.
The remaining 50% of the dataset will be iterated and test the model.
The ARIMA(p,d,q) model requires three parameters and is traditionally configured manually.
Use an ARIMA(0,1,0) on the raw data may be a good starting point.
When model trained, a one-step prediction made ang the prediction stored for later evaluation.
The actual observation from the test dataset woll be added to the training dataset for the next iteration.
The predictions made during the enumeration of the test dataset will be evaluated and an RMSE score reported.
Calculate the RMSE using the helper function from the scikit-learn library, from dataset only
Those RMSE will show you on average, how much the error/the model was wrong/gap between predection and expected value per capita per day for each prediction made.
