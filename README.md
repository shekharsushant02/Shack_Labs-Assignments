# Shack_Labs-Assignments

Project: House Price prediction using several ML Algorithms

Problem statement: The goal is to understand the relationship between house features and how these
variables affect the house price.
Using more than one model, predict the price of the house using the given dataset. Please compare the
accuracy of the models

# Libraries and Frameworks Used
Numpy

Pandas

Matplotlib

Seaborn

Scikit-learn

Scipy

# Machine Learning Algorithms Used 
RandomForest

LinearRegression

SVM

DecisionTree

KNN

# Evaluation of Model Performances using their R2 Score


|  Models       | R2 Score      |
| ------------- |:-------------:| 
| Random Forest Regressor      | 0.755318 | 
| LinearRegression     |  0.643865    |  
| SVR |     0.592828 |  
|DecisionTree Regressor| 0.543304|
|KNeighborsRegressor | 0.54228 |

# R2 Score 

* The R2 score is a very important metric that is used to evaluate the performance of a regression-based machine learning model. It is pronounced as R squared and is also known as the coefficient of determination. It works by measuring the amount of variance in the predictions explained by the dataset.
* The higher the R-squared, the better the model fits your data.
* We will use Random Forest Regressor as it gives the best R2 score with 75.53% Accuracy.
