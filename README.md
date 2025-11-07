# Introduction
This repository contains practical Application Assignment III (module 17). It uses  the UCI Bank Marketing Dataset (bank-additional-full.csv, located in the data folder). The notebook builds and evaluates classification models to predict which customers are likely to accept a long-term deposit offer, based on features such as job, marital status, education, housing loan, and personal loan.

The project compares the performance of the following classifiers:

Logistic Regression
K-Nearest Neighbors (KNN)
Decision Trees
Support Vector Machines (SVM)

For all models, both training time and accuracy are recorded to assess the classifier which performs best in predicting customer responses during a phone-based marketing campaign.  GridSercvCV is used for each model to compate the results.

According to the Materials and Methods section, the number of marketing campaigns that the data represents is 17 , the exact exceprt is "The dataset collected is related to 17 campaigns that occurred between May 2008 and November 2010, corresponding to a total of 79354 contacts."

# Observations
With respect to varius features following observationa were made on the data
Education - for the termdeposit the bank was successul to seel the product to university degree folks
Job - for the term deposit the bank wbank had the most success with folks in admin role,followed by Technician and then blue-collar
Marital Status - for the termdeposit the bank was successful to sell the product to married vs single
Housing - Not significat difference between customers have mortagage loan or not
Contact - For the termdeposit the bank was successful to sell the product to cellphone users vs telephone users

# Business Objective 
From a business objective, of the task is to determine the factors could lead to a higher success rate, for example,
The business goal is to identify the factors that lead to a higher campaign success rate. including factors like housing mortgage, contact method (cell phone, telephone), personal loans, age , job, university degree etc.
The campaigns show some success in some categories but the results doesn't seem to be too successful.

# Model Comparison Results
For the baseline model, decided to use a DummyClassifer which is a very good choice as it just separates the classes.

This model was compared with a Logistic Regression model, a statistical method used to examine how one or more independent variables influence a categorical dependent variable.

In training, fitting and predicting both models on the dataset, the following results were observed:
![Alt text](images/filename.png)



