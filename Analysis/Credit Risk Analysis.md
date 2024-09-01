## Credit Risk Classification Analysis 

The purpose of the analysis is to build a model that can identify the crediworthiness of borrowers.

The lending data provided included loan size, interest rate, borrower income, number of accounts, derogatory marks and total debt.
Based off of this information we were tasked with predicting the creditworthiness of the borrowers.

Using the machine learning processes of logistic regression the data was separated into training and testing datasets using train_test_split from sklearn.model_selection.  Predictions were conducted and then evaluated using a confusion matrix and classification report to determine how well the prediction model worked.


## Results

Machine Learning Model 1 Logistic Regression: Predicting Healthy Loans

    * Precision:The model had a 100% precision ratio - meaning 100% of the predictions were correct.

    * Accuracy: 99%

    * Recall: The model was 100% accurate in predicting Healthy Loans

Machine Learning Model 2 Logistic Regression: Predicting High-Risk Loans

    * Precision: The model had a 87% precision ratio - meaning 87% of the predictions were correct.

    * Accuracy: 99%

    * Recall: The model was 95% accurate in predicting High-Risk Loans

## Summary

While the model was 100% accurate in predicting Healthy Loans, I would recommend additional sampling to increase the precision and 
recall of High-Risk loans.