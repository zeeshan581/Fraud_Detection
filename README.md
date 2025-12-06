# Credit Card Fraud Detection Using Machine Learning

 ## ABSTRACT
In this project, we build machine learning models to predict whether a credit card transaction is fraudulent or not.
The dataset contains transactions made by European cardholders in September 2013 over a period of two days. Out of 284,807 total transactions, only 492 are frauds, which makes the dataset highly imbalanced (fraud cases = 0.172%).
Due to confidentiality, most input features (V1–V28) were transformed using PCA (Principal Component Analysis). Only Time, Amount, and Class are non-PCA features.

The dataset is available on Kaggle here:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
<br>
<br>

## Models Used

We trained and evaluated the following machine learning models:

Logistic Regression,
Random Forest Classifier,
K-Means Clustering (unsupervised baseline)

<br>
<br>

## Results

Among all the models evaluated, the Random Forest Classifier achieved the best performance, with an accuracy of 99.9859%, and perfect scores for precision, recall, and F1-score, successfully identifying all fraudulent transactions in the test dataset. Logistic Regression also performed well as a baseline model, achieving an accuracy of 94.48% and a recall of 0.915, although it missed more fraud cases compared to Random Forest. In contrast, the K-Means clustering algorithm performed poorly, with an accuracy of 53.47% and a recall of only 0.0847, demonstrating that unsupervised clustering is not suitable for this type of supervised fraud classification task.

<br>





