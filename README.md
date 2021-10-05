# **Ritika_Portfolio**

# [Project 1: Sales forecasting for a food & beverage retailer](https://github.com/ritikatiwarii/food_retail_forecasting)
Created a forecasting model for a department under chilled category of a F&B retailer
* Loaded 3 years of sales history from Jan 2018 to Feb 2021 into a dataframe.
* Fixed data anomalies like missing dates in the time series by adding the day with 0
* Did Exploratory data analysis using visualizations and decomposition of the series into trend, seasonality, residual
* Performed Anomaly(Outlier) detection on the series and capped the outliers to the mean of sales in last 6 months. 
* Divided the series into test and train dataset. The sales before and including 1st Jan 2021 was taken as part of training set and after 1st Jan was taken as test ing set. 
* Defined the performance measurement of the forecast
* Fit the model on the training dat
* Used the model to predict the data for the test data time period. 
* Recorded the performance of the model

# **Project 2: Store allocation logic in python**
Challenge - If we have 'x' quantities of a product in the warehouse and the x needs to be distributed among 'n' stores. What would be one of the best ways to do it?

