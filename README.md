# Credit-Card-Fraud-Detection-Using-Hybrid-Model

## Data Source: https://www.kaggle.com/mlg-ulb/creditcardfraud

It is a CSV file, contains 31 features, the last feature is used to classify the transaction whether it is a fraud or not.


**Information about dataset**
* The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
* It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues original features are not provided and more background information about the data is also not present. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
* Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.

## Problem Statement
In this project we want to identify fraudulent transactions with Credit Cards. Our objective is to developed a Hybrid Model which consists of Random Forest, K-Nearest Neighbors, and Artificial Neural Network Algorithms using the Majority Voting Approach for detecting frauds in Credit Card effectively.

## Business Problem Overview
* For many banks, retaining high profitable customers is the number one business goal. Banking fraud, however, poses a significant threat to this goal for different banks. In terms of substantial financial losses, trust and credibility, this is a concerning issue to both banks and customers alike.

* It has been estimated by Nilson report that by 2020 the banking frauds would account to $30 billion worldwide. With the rise in digital payment channels, the number of fraudulent transactions is also increasing with new and different ways.

* In the banking industry, credit card fraud detection using machine learning is not just a trend but a necessity for them to put proactive monitoring and fraud prevention mechanisms in place. Machine learning is helping these institutions to reduce time-consuming manual reviews, costly chargebacks and fees, and denials of legitimate transactions.

## Prerequisites
You need to have installed following softwares and libraries in your machine before running this project.

* Python 3
* Anaconda: It will install ipython notebook and most of the libraries which are needed like pandas, seaborn, matplotlib, numpy, sklearn, tensorflow.

## Architecture
The project architecture deployed is shown here.
![Picasc](https://user-images.githubusercontent.com/70885585/129890396-b5cbdcc6-24d4-4a45-bca5-4cf600a2acda.png)

## Result
The Precision, Recall, F-1 score, and Accuracy value of the Hybrid approach respectively were 0.95, 0.79, 0.85, and 0.9994967.

<img src="https://user-images.githubusercontent.com/70885585/129950395-c97d7c47-2e67-447c-b5ff-842c1b4b1005.png" width="400" height="150">

Comparison of key performance indicators between the tested approaches:

<img src="https://user-images.githubusercontent.com/70885585/129953665-5078f0db-f093-4b2f-b9de-0fe23240602d.png" width="450" height="250">



