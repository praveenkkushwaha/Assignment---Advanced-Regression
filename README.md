# Assignment - Advanced Regression
##### A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.The company is looking at prospective properties to buy to enter the market

# Business Goal
##### We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

# Aim of Analysis
##### We are required to build a regression model in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
- The company wants to know which variables are significant in predicting the price of a house
- How well these variables describe the price of a house.
- Company has collected Data from the sale of houses in Australia

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- House those have `OverallOual` rated as `5` and `6` are maximum
- An Interesting Pattern can be seen here, `SalePrice` of the houses which has more `GarageCars` capacity are Expensive even for same `LotArea` and also for same Car Capacity Garages Houses which have Roughly Finished or Finished Garages are Expensive
- FV - Floating Village Residentials` and `RL - Residentials Low Density ` have highest Sales Price
- Columns that are showing strong correlation with Target Column :- `OverallQual` , `LotArea`,`YearBuilt` , `YearRemodAdd` , `GarageArea` ,`GarageCars`,`GarageYrBuilt`,`FirePlaces`,`TotRmsAbvGrd` ,`GrLivArea`,`1stFlrSF` , `TotalBsmtSF`
- Columns Showing strong correlation to each other:- `YearBuilt`  and `GarageYrBuilt` ---- 0.78,` TotalBsmtSF` and `1stFlrSF` ---- 0.81,`GrLivArea` and `TotRmsAbvGrd` ---- 0.83,`GarageCars` and `GarageArea` ---- 0.89
- alpha for Ridge  is `50` , alpha for Lasso  is `0.005`

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas Version 2.0.3
- scikit-learn Version 1.3.0
- matplotlib Version 3.7.1
- numpy Version 1.24.3
- seaborn Version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@praveenkkushwaha] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
