# StockPriceLinearRegression

Project: Build a ML model to predict the top 5 companies with highest quarterly returns

Design: 
1.	Split the data into training data and test data. We will train the model using data from starting period 31 Dec 2010 to End period 31 Dec 2020 and we will test the data using data from starting period 31 Dec 2020 to End period 31 March 21. 
2.	Clean data and convert values to float. Delete all rows with at least 1 NA value. 
3.	Plot correlation matrix and remove features where there are correlation > 0.7 to reduce multicollinearity 
4.	Train model using training data 
5.	Input test data into model and compare predicted results to actual results 
6.	Calculate r-squared 
