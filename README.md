# credit-risk-classification

In this analysis, we evaluated the credit risk of borrowers using a logistic regression model. The dataset consists of financial information such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The goal was to predict whether a loan would be classified as healthy (0) or high-risk (1). The machine learning process involved loading and preprocessing the dataset, separating the target variable (loan_status) from the feature variables, splitting the dataset into training and testing sets using the train_test_split method, training a logistic regression model on the training data, and evaluating the model’s performance using a confusion matrix and classification report.

For the logistic regression machine learning model, the accuracy was 99%. 

![classification_report.png](https://github.com/otybaasandorj/credit-risk-classification/blob/main/Credit_Risk/images/classification_report.png)

The logistic regression model demonstrates excellent performance, achieving an overall accuracy of 99%. The model performs exceptionally well for predicting healthy loans (0), with perfect precision, recall, and F1-scores. For high-risk loans (1), the model also performs well, with an F1-score of 0.91, despite some trade-offs in precision. Given the importance of identifying high-risk loans for mitigating financial losses, the model is effective and suitable for deployment. However, if further improvements are desired, techniques like resampling, hyperparameter tuning, or exploring alternative algorithms could address any class imbalance or refine performance on high-risk predictions.

This logistic regression model can be used by the company to assess credit risk effectively. The high accuracy and precision ensure it will reliably predict healthy loans while still maintaining a strong ability to detect high-risk cases.
