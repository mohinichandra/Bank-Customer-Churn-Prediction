# Bank-Customer-Churn-Prediction

![Customer-Churn](https://github.com/micky-26/Bank-Customer-Churn-Prediction/assets/106061980/2a1e89ce-8cbb-422b-8285-b5521215fa4e)

Customer churn or customer attrition is a tendency of clients or customers to abandon a brand and stop being a paying client of a particular business or organization.
The percentage of customers that discontinue using a company’s services or products during a specific period is called a customer churn rate. Several bad experiences (or just one) are enough, and a customer may quit. And if a large chunk of unsatisfied customers churn at a time interval, both material losses and damage to reputation would be enormous.

A reputed bank “ABC BANK” wants to predict the Churn rate. Create a model by using different machine learning approaches that can predict the best result.

WORK FLOW :

In order to create a model these are the following procedure -

1. Split the dataset in 70% of Train set and 30% of Test Set
2. Feature engineering
3. Check the accuracy score for both Training and Test Set
4. Compare the accuracies for both Training and Test set, in order to check for the overfitting issues.
5. Save the model for futher prediction

OUTPUT:

From the review of the fitted models, the best model that gives a decent balance of the recall and precision is the random forest where according to the fit on the training set, with a precision score  of 0.86, out of all customers that the model thinks will churn, 86% do actually churn and with the recall score of 0.86.
