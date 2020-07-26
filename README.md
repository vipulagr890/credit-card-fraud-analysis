# credit-card-fraud-analysis
In the following project, I have created machine learning pipeline to determine fraud credit card transaction. 

# Problem Statement:

The credit card fraud transaction is a big problem for the banks and the individuals who lost their money due to this scams.
In the following ML model we have classified the fraud transaction and then the model is used to idetify whether the any new transaction is fraudlent or not.

#Data Insights:
1.Our dataset contains of 287,807 transaction observations out of which only 492 are fraud transaction. Hence the data is highly skewed.
  and can is justified as the fraud transaction are relatively low compared to normal transactions.
 
2. The dataset consists of numerical values from the 28 ‘Principal Component Analysis (PCA)’ transformed features, namely V1 to V28. 
Furthermore, there is no metadata about the original features provided due to security purpose of the individual data,
so pre-analysis or feature study could not be done.

3. There is no missing value in dataset.

4. The 'Time' and 'Amount' features are not transformed dataset.

# Model Insights:

In the following analysis we have used Logistic regreession for our classification problem but as we can see from our confusion mtrix, we still have around 
99 wrong classified transaction which can be huge in a real world scenerio.

So to improve our model performance we will use SVC and ensembel techniques for the classisfier.

date for next release: 2 august 2020.
