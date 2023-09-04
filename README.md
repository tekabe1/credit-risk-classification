# credit-risk-classification

Overview of the Analysis
The purpose of this analysis is to develop a machine learning model to predict credit risk for loans based on various financial features. The dataset contains information about loan size, interest rate, borrower income, debt-to-income ratio, the number of accounts, derogatory marks, total debt, and loan status (0 for healthy loans and 1 for high-risk loans). The primary goal is to build a model that can accurately classify loans as either healthy or high-risk.

The analysis involves the following stages:

1. Data Preparation: Separating the dataset into features (X) and the target variable (y), which is loan status. Additionally, checking the balance of target values reveals a significant class imbalance.

2. Initial Model (Imbalanced Data): Training a logistic regression model on the imbalanced dataset and evaluating its performance.

3. Resampling: Addressing class imbalance using random oversampling to create a balanced training dataset.

4. Improved Model (Resampled Data): Training a logistic regression model on the resampled data and evaluating its performance.

5. Evaluation: Calculating various metrics like accuracy, precision, recall, and F1-score to assess the models' effectiveness.

The Results
Initial Model (Imbalanced Data):
• Balanced Accuracy Score: 0.952
• Precision Score (Class 0): 1.00
• Precision Score (Class 1): 0.85
• Recall Score (Class 0): 0.99
• Recall Score (Class 1): 0.91
Improved Model (Resampled Data):
• Balanced Accuracy Score: 0.994
• Precision Score (Class 0): 1.00
• Precision Score (Class 1): 0.84
• Recall Score (Class 0): 0.99
• Recall Score (Class 1): 0.99
Summary
The analysis demonstrates that the machine learning model, trained on the resampled data with random oversampling, performs exceptionally well in predicting credit risk for both healthy and high-risk loans. The improved model achieved a balanced accuracy score of approximately 0.994, indicating strong overall performance. It exhibits high precision, recall, and F1-scores for both classes.

Recommendation:
Considering the high accuracy, precision, and recall scores, I recommend using the improved logistic regression model trained on the resampled data for credit risk assessment. This model effectively addresses the class imbalance issue and provides robust predictions for loan categorization. It is suitable for the company's credit risk analysis and can help in making informed decisions regarding loan approval.
