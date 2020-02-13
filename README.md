# churn_modelling
Predicting whether a customer leaves your service or product based on their behaviour, credit score and other parameters.

# Description

A Predictive Churn Model is a tool that defines the steps and stages of customer churn, or a customer leaving your service or product. Having a predictive churn model gives you awareness and quantifiable metrics to fight against in your retention efforts.
 
I have been given a dataset Churn_Modelling.csv which contains columns as RowNumber, CustomerId, Surname, CreditScore, Geography, Gender, Age, Tenure, Balance, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary and Exited.

Leaving the service or product means 1 in Exited attribute, otherwise 0.

Based on these parameters I have trained a model to predict whether a customer leaves your service given that all these parametrs of that particular customer.

I used sklearn, keras, matplotlib.pyplot, pandas, numpy libraries and gained an accuracy of 82.5 with loss of 39.2.
