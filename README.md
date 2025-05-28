# Project Overview
Customer churn is a critical challenge in the telecom industry. This project applies machine learning to predict whether a customer is likely to churn, using real-world telecom data and XGBoost. It emphasizes preprocessing, feature engineering, model evaluation, and handling imbalanced classes to create a robust predictive pipeline.

The data is sourced from IBM's Base Samples. More information about the data can be found here: https://community.ibm.com/community/user/blogs/steven-macko/2019/07/11/telco-customer-churn-1113

Insights:
- The data is imbalanced, with churning customers being the minority group.
- Application of Synthetic Minority Oversampling Technique (SMOTE) to balance the data and hyperparameter tuning improved model performance and churn prediction.
- Monthly Charges, Total Charges, and Tenure were the most important features in the model. Contract type is the next highest in importance.
