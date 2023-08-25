# credit-risk-classification
## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of analysis is predict the risk of giving loan.
* The dataset has the fields of loan_size,	interest_rate,	borrower_income,	debt_to_income,	num_of_accounts,	derogatory_marks,	total_debt and	loan_status.
* We have to predict the loan status of borrowers, with 0 being 'healthy loan' and 1 being 'high rosk loan.
* The features and lables were identified and they were separated as X and y, then the data was split into test and train. A logistic regression model was fitted by using the training data.
* Then the predictions were saved  on the testing data labels by using the testing feature data (X_test) and the fitted model.
* After that the model"s performance was evaluated using confusion matrix and accuracy score.
* In the end, classifiaction report was printed
  

## Results

* The accuracy score of the model is 0.9918489475856377 which is high.
* The precision score for 0 is .997 almost 1 and recall score is .99.
* The precision score for 1 is .85 and recall score is .91

## Summary

* The logistic regression model that we have used is pretty accurate at predicting the loan status of borrowers. It has a high accuracy rate and precision scores are good too.

