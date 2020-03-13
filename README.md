# Boston-Housing-Price-Case-Study

PROBLEM AND APPROACH

The Boston housing dataset is a classic benchmark dataset in data mining area. Using exploratory data analysis we understood the data, distribution of the features, presence of potential outliers and used machine learning models to identify the most important features for predicting the median housing prices.

The dataset “Boston” on Boston Housing Price is taken from the MASS library of R. It has 506 observations and 14 attributes. Below is a brief description of each feature of the dataset:

1.	CRIM     – 	per capita crime rate by town
2.	ZN     – 		proportion of residential land zoned for lots over 25,000 sq.ft
3.	INDUS     – 	proportion of non-retail business acres per town
4.	CHAS     – 	Charles River dummy variable (1 if tract bounds river; else 0)
5.	NOX     – 	nitric oxides concentration (parts per 10 million)
6.	RM     – 	average number of rooms per dwelling
7.	AGE     – 	proportion of owner-occupied units built prior to 1940
8.	DIS     – 	weighted distances to five Boston employment centres
9.	RAD     – 	index of accessibility to radial highways
10.	TAX     –	 full-value property-tax rate per $10,000
11.	PTRATIO     – 	pupil-teacher ratio by town
12.	B     – 		1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
13.	LSTAT     – 	% lower status of the population
14.	MEDV     – 	Median value of owner-occupied homes in $1000’s


RESULTS

Various machine learning models i.e Linear Regression , CART, Bagging, Random Forests, Boosting and XG-Boost were implemented in R for predicting the median housing prices. 

In order to compare the performance of all models, MSE was used as the evaluation metric. 

It was found that Random Forests, Gradient Boosting and XG-Boost did good both for in-sample and out of sample predictions. Gradient Boosting however outperformed Random Forests for in-sample data leaving us further scope for checking possible case of overfitting. 


The most important features highlighted by Ensemble Methods were closely similar. Lsat, rm and dis were the most important features in predicting the median housing prices in Boston. 
