# Module 12 Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis was to determine the creditworthiness of borrowers from peer-to-peer lending services data.
* The data provided had loan size, interest rate, borrower income, debt to income ratio, # of accounts, derogatory marks, total debt, and loan status. The objective was to predict if a loan provided to the borrower would be healthy or high risk. 
* In the data provided, 75k (96.7%) rows were labeled as healthy loans and 2.5K (3.3%) were labeled as high-risk loans.
* There were several stages in the machine learning process:
  1) Spliting the data into training and testing sets
  2) Creating a logisitic regression analysis with the original data
  3) Predicting a logitistic regression analysis with resampled training data.
* I used sklearn.linear_model to import LogisticRegression as well as using imblearn.over_sampling to import RandomOverSampler to resample the data.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1 (High-Risk Loans):
    * balanced accuracy = 99.5%
    * precision = 87%
    * recall = 100%
    * f1-score = 93%



* Machine Learning Model 2 (High-Risk Loans):
    * balanced accuracy = 99.5%
    * precision = 87%
    * recall = 100%
    * f1-score = 93%

I ran the first model several times to fix code mistakes and I believe the model trained to a more accurate degree than expected. Originally the high-risk loan scores were lower than currently shown. I expected the 2nd Machine Learning model to provide a more accurate outcome.

## Summary

Random Oversampling should have performed better. I ran the first model several times to fix code mistakes and I believe the model trained to a more accurate degree than expected. Originally the high-risk loan scores were lower than currently shown. I expected the 2nd Machine Learning model to provide a more accurate outcome. High-risk loans have a lower performance of predicting so more sample data from "1's" would be needed to have better performance.
