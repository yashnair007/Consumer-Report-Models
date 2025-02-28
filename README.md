# Consumer-Report-Models

All the outputs are visible in the Notebook itself.

Overview

This project performs text classification on the Consumer Complaint Database provided by the U.S. Consumer Financial Protection Bureau (CFPB). The goal is to classify consumer complaints into the following categories:

0 - Credit reporting, repair, or other

1 - Debt collection

2 - Consumer Loan

3 - Mortgage

Dataset
The dataset can be accessed at https://catalog.data.gov/dataset/consumer-complaint-database

Features
Data Preprocessing: Cleans and preprocesses complaint text, including tokenization, stopword removal, and lemmatization.

Feature Engineering: Uses TF-IDF vectorization to convert text into numerical representations.

Model Training: Implements and evaluates multiple machine learning models:

Naïve Bayes

Logistic Regression

Support Vector Machine (SVM)

XGBoost

Evaluation Metrics: Uses classification reports and confusion matrices to assess model performance.

Model Persistence: Saves the trained TF-IDF vectorizer and XGBoost model using Pickle.

Prediction Functionality: Provides a function to predict the category of new complaints.

Dependencies

pandas

numpy

scikit-learn

xgboost

nltk

Future Enhancements

Implement deep learning models for improved accuracy.

Optimize hyperparameters using GridSearchCV.

Deploy as an API using Flask/FastAPI.
