Predicting-Big-mart-sales

The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and find out the sales of each product at a particular store.Using this model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales.

I first cleaned the data, fixed the mismatch in data entry and also filled the null values with suitable value.

I visualised the data and created dummies for the categorical data and then went forward to build a simple linear regression model.

I divided the dataset into test and train sets and using the RFE we determined the important variables affecting the sales.

Looking at the P-values and the VIF's we decided on the features to retain in our model.

Doing the residual analysis on the train data to see for it's normality assumption and then using our model on the test data.
