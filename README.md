# Predicting Credit Card Approvals

## Dataset
Pulled raw credit card approval data from UCI Machine Learning repository.
All the datasets used are posted here for reproducibility.

## Description
* Preprocessed data by imputing missing values using mean imputation, converted non-numeric to numeric data using label encoding, split data into train set and test set.
* Fit logistic regrssion model into train set which resulted with an accuracy score of 84%.
* Performed grid search using scikit-learns hyperparameters: tol and max_iter functions to tweak the models performance. This function performed a cross validation of 5 folds.
* Predicted the possibility of credit card approval rate by evaluating the best score and best hyperparameter.

## Source credit
http://archive.ics.uci.edu/ml/datasets/credit+approval
