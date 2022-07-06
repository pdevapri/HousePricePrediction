# House Price Prediction
> Surprise Housing uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The company is looking at prospective properties to buy to enter the market . We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.
Also, to determine the optimal value of lambda for ridge and lasso regression.

## Table of Contents
* [General Info](#general-information)
* [Steps followed](#steps-followed)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The company is looking at prospective properties to buy to enter the market. We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Steps Followed
- Analysing the Data and Data Visualization
- Data Cleaning and Data Manipulation
- Creating dummy variables
- Train-Test split
- Rescaling of Data
- Building the model- Linear Regression
- Building the model- Ridge Regression
- Model Evaluation with differnt values of lambda
- Determining the optimal value of lambda
- Building the model- Lasso Regression
- Model Evaluation with different values of lambda
- Determining the optimal value of lambda


## Conclusions
- The optimal value of lambda for Ridge regression is 2
- The optimal value of lambda for Lasso regression is 0.001
- The top five factor impacting the price are - GrLivArea, 1stFlrSF, 2ndFlrSF, MasVnrArea, FullBath
- A unit increase in GrLivArea can possibly increase the House price by 0.115 units
- A unit increase in 1stFlrSF can possibly increase the House price by 0.104 units
- A unit increase in 2ndFlrSF can possibly increase the House price by 0.082 units
- A unit increase in MasVnrArea can possibly increase the House price by 0.060 units
- A unit increase in FullBath can possibly increase the House price by 0.056 units

