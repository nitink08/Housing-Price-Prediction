# Housing Price Prediction


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.

### The company is looking at prospective properties to buy to enter the market.

### The company wants to know:
* Which variables are significant in predicting the price of a house, and
* How well those variables describe the price of a house.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
#### The Optimal Lambda values in case of Ridge and Lasso are:

-  Ridge - 5
-  Lasso - 0.0004

#### The Mean Squared error in case of Ridge and Lasso are:
 
-  Ridge - 0.01371078357735112
-  Lasso - 0.013535752335222997

#### The Mean Squared Error of Lasso is slightly lower than that of Ridge.

#### As we know Lasso helps in feature reduction (as the coefficient value of one of the feature became 0), Lasso has a better edge over Ridge.

#### So based on Lasso, the factors that generally affect the price are the 
-  Zoning classification
-  Living area square feet
-  Overall quality and condition of the house
-  Foundation type of the house
-  Number of cars that can be accomodated in the garage
-  Total basement area in square feet and the Basement finished square feet.

#### Therefore, the variables predicted by Lasso in the above bar chart as significant variables for predicting the price of a house.


## Technologies Used
- numpy - version 1.21.5
- pandas - version 1.4.4
- matplotlib.pyplot - version 3.5.2
- seaborn - version 0.11.2

- sklearn.preprocessing -> scale - version 1.0.2
- sklearn.model_selection -> train_test_split - version 1.0.2
- sklearn.linear_model -> Ridge, Lasso - version 1.0.2
- sklearn.metrics -> mean_squared_error - version 1.0.2
- sklearn.model_selection -> GridSearchCV - version 1.0.2

- sklearn.feature_selection -> RFE - version 1.0.2
- sklearn.linear_model -> LinearRegression - version 1.0.2
- statsmodels.api - version 0.13.2
- sklearn -> metrics - version 1.0.2

## Acknowledgements
- This project was inspired by US-based housing company named Surprise Housing.

## Contact
Created by [@nitink08] - feel free to contact me!
