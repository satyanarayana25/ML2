# House Price prediction
> Outline a brief description of your project.

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

Business Goal

The model is price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
Assignment Part-II

Question 1

What is the optimal value of alpha for ridge and lasso regression? What will be the changes in the model if you choose double the value of alpha for both ridge and lasso? What will be the most important predictor variables after the change is implemented?

Question 2

You have determined the optimal value of lambda for ridge and lasso regression during the assignment. Now, which one will you choose to apply and why?

Question 3

After building the model, you realised that the five most important predictor variables in the lasso model are not available in the incoming data. You will now have to create another model excluding the five most important predictor variables. Which are the five most important predictor variables now?

Question 4

How can you make sure that a model is robust and generalisable? What are the implications of the same for the accuracy of the model and why?
Business Goal

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market. Ridge and Lasso

Regeression


## Table of Contents
* OverallQual vs Sales
* Neighborhood vs sales


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- after doing the EDA on data provide ppl are spending more money on buy the house which has the walking place and good comfort area and in good neighborhood and new building as well.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Data Preparation:
- train and split 
- 70% as training data
- 30% as test data
- MinMax Scalling.


## Conclusions
- lasso regression is better when we compare with ridge
R2_Score on train set:  0.9300994903116862
R2_Score on test set:  0.9144293099107396

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas version - version 1.3.4
- numpy version - version 1.20.3
- sea born version - version 0.11.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@satya] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
