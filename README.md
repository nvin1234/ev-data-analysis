This project focuses on predicting fraudulent financial transactions using machine learning.
The dataset consists of 6.3M+ transactions and 10 features, provided as part of a business case challenge.
The goal was not only to build an accurate fraud detection model but also to derive business insights and recommend preventive strategies for financial institutions.
Contains details of transactions labeled as fraudulent (1) or genuine (0)


Dataset
Rows: ~6,362,620
Columns: 10
Source: Provided dataset link

Steps Followed
1. Data Cleaning
Handled missing values and outliers
Checked multicollinearity between features
Performed normalization and encoding where required
2. Exploratory Data Analysis (EDA)
Fraud vs Non-Fraud distribution (highly imbalanced)
Relationship between transaction amount, time, and fraud probability
Plotted histograms, correlation heatmaps, and bar plots
Feature Selection
Removed highly correlated variables
Selected top features based on correlation + Random Forest importance
4. Model Development
Trained and compared multiple models:
Logistic Regression
Decision Tree
Random Forest (best performance)
Insights

High transaction amount increases fraud probability

Mismatch in location/device is a strong predictor
Unusual transaction frequency is another key indicator
 Business Recommendations
Implement real-time alerts for unusual transactions
Multi-factor authentication for high-value transactions
Regular infrastructure updates to detect anomalies early
