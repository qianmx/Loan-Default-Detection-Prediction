# Loan-Defaults-Prediction

**Key Word: Spark(pyspark), Distributed Computing, AWS(S3,EMR), Machine Learning**

##Introduction
This project aims to predict defaults of LeandingClub loans. 

##Data
The data is downloaded from Kaggle- Lending Club Loan Data(https://www.kaggle.com/wendykan/lending-club-loan-data), with 73 features, and 880,000 observations.

The data is uploaded into AWS S3.

##Modeling
* Logistic Regression and RandomForest are used to predict whether the customer will default.
* EDA, Feature Engineering, and modeling are tested in local machine using Spark, and are then deployed to AWS-EMR. 

##Output

* Oversampling is used to deal with unbalanced data and improved model performance.
* The inital model performace and final model performance are shown below. 

![alt tag](https://github.com/qianmx/Loan-Defaults-Prediction/blob/master/gitplot/output1.png)

![alt tag](https://github.com/qianmx/Loan-Defaults-Prediction/blob/master/gitplot/output2.png)








