# Credit Card Fraud Detection
# Problem Statement
Fraudulent activities have increased severalfold, with around 52,304 cases of credit/debit card fraud reported in FY'19 alone.
Due to this steep increase in banking frauds, it is the need of the hour to detect these fraudulent transactions in time in order to 
help consumers as well as banks, who are losing their credit worth each day. Every fraudulent credit card transaction that occur is a direct
financial loss to the bank as the bank is responsible for the fraud transactions as well it also affects the overall customer satisfaction adversely.

# Data Source: https://www.kaggle.com/mlg-ulb/creditcardfraud
The data set that you will be working on during this project was obtained from Kaggle. It contains thousands of individual transactions that took place over
a course of two days and their respective labels.

As you saw, the data set includes credit card transactions made by European cardholders over a period of two days in September 2013. 
Out of a total of 2,84,807 transactions, 492 were fraudulent. This data set is highly unbalanced, with the positive class (frauds) accounting for
just 0.172% of the total transactions. The data set has also been modified with Principal Component Analysis (PCA) to maintain confidentiality. 
Apart from ‘time’ and ‘amount’, all the other features (V1, V2, V3, up to V28) are the principal components obtained using PCA. The feature 'time'
contains the seconds elapsed between the first transaction in the data set and the subsequent transactions. The feature 'amount' is the transaction amount.
The feature 'class' represents class labelling, and it takes the value 1 in cases of fraud and 0 in others.

The distribution plots of the variables were Gaussian, which might indicate the effects of transformations that had already occurred on the data set.

# High Level Lifecycle steps
- Exploratory data analysis
- Model Building
- Models used built and explored :
  - KNN
  - SVM
  - Decision Tree
  - Random Forest
  - XGBoost
- Model Hyper parameter tuning ,applying SMOTE
- Model predictions
- Tracking and observing output accuracy and related model scores 
