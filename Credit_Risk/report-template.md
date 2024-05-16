# Credit Risk Analysis

## Overview of the Analysis
* The purpose of the analysis is to evaluate performance for a Machine Learning Model using Logistic Regression. Our goal is to predict the credit risk associated with loans based on a number of variables. The data used for this analysis is financial lending data that focuses on loans: loan size, interest rate, borrower income, det-to-income ratio, number of accounts, derogatory marks, and total debt. With this data, the model will predict the loan status as either a healthy loan(0) or a high-risk loan (1).

* The stages of the machine learning process that were used in creating this report are: 
    * Splitting the data into training and testing datasets. 
    * Creating and fitting a logistic regression model. 
    * Evaluating model performance using accuracy, precision, and recall scores.
* Logisitic Regression was the method used in completing this analysis. 

## Results

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
        * Accuracy: The overall accuracy of the model is 0.99 which shows that it classifies 99% of the instances correctly. 
        * Precision: The precision for Healthy loans (0) is 1.00, which means that the model does very well in identifying true positives and very few false positives. For High-risk loans(1), the model has a precision of 0.87, showing that it is mostly effective when identifying high-risk loans with some false positives. 
        * Recall: Healthy loans(0) have a recall of 1.00, meaning the model is correclty identifying nearly all instances of healthy loans with very limited false negatives. High-risk loans(1) have a recall of 0.89, indicating that the model is identifying high-risk loans with some false negatives. 

## Summary

Based on the results of the Machine Learning Model, I would recommend that company uses the model while continuing to improve the model. While precision is 0.87 for high-risk loans, the model will correctly identify high-risk loans the majority of the time with some false positives. This results in some loans being identified as high-risk but ultimately having no issues. With continued improvements to the model, these scores can improve and the accuracy of the model would improve as well. For a lendor, this would allow them to identify potenital risk, monitor potential risk, and take necessary actions. 