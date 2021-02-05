# Predicting the Sale Price of Bulldozers 
<hr>

## Problem Definiton

How well we can predict the future sale price of a bulldozer, given its characteristics and previous examples of how much similar bulldozers have been sold for?

## Libraries Used:-
* Numpy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn

## Data

The data is downloaded from the Kaggle Bluebook for Bulldozers competition : <br>
https://www.kaggle.com/c/bluebook-for-bulldozers/data

## Evaluation
The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.<br>
For more evaluation of this project :- https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation

## Features
Feature information details are given in the Data Dictionary.xlsx<br>
https://www.kaggle.com/c/bluebook-for-bulldozers/data

## Approach:-
* Exploratory Data Analysis
* Data Preprocessing
* Fixing Null values
* Modelling (Random Forest Regressor)
* Hyper Parameter Tuning (RandomizedSearchCV)

**Reaching Training accuracy of approx 98.6% and Validation accuracy of approx 87.06%**<br><br>
**Training data RMSLE is 0.08**<br>
**Validation data RMSLE is 0.25 which can be treated as equal to Test data**(as we can't now find RMSLE of Test data as competition is closed)

### Random Forest feature importance
![feature](https://user-images.githubusercontent.com/67990422/107074686-14eff380-680f-11eb-9cce-cea23e4ce566.png)
