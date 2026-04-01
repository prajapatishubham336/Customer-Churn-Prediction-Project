# Customer-Churn-Prediction-Project
Customer churn is a major challenge for businesses, especially in banking and telecom sectors. This project uses machine learning models to predict whether a customer is likely to leave the service. By analyzing features like credit score, age, geography, and balance, the model identifies churn patterns. These insights help businesses take proactive steps to improve customer retention.


📌 Project Overview

Customer churn is a major concern for businesses, especially in banking and telecom sectors. This project aims to predict whether a customer will leave the service using machine learning models.

By analyzing customer data such as credit score, geography, age, and balance, we build predictive models to identify churn behavior.

🎯 Objective

Predict whether a customer will churn (Exit = 1) or not (Exit = 0)
Compare performance of multiple machine learning models
Improve business decision-making using data insights

🚀 Features

Data preprocessing and cleaning
Exploratory Data Analysis (EDA)
Feature encoding and scaling
Model training using:
Logistic Regression
Random Forest Classifier
Model evaluation using:
Accuracy Score
Confusion Matrix
Classification Report

🛠️ Technologies Used

Python 🐍
Pandas & NumPy
Matplotlib & Seaborn
Scikit-learn

📂 Dataset

The dataset used in this project is publicly available on Kaggle:

🔗 https://www.kaggle.com/datasets/shubhendra7/customer-churn-prediction

Dataset Features:
CreditScore
Geography
Gender
Age
Tenure
Balance
NumOfProducts
HasCrCard
IsActiveMember
EstimatedSalary
Exited (Target Variable)

🔹 Data Preprocessing Steps

Removed unnecessary columns:
RowNumber
CustomerId
Surname
Encoded categorical variables:
Geography
Gender
Feature scaling using StandardScaler
Split dataset into:
Training set
Testing set

⚙️ How It Works

Load dataset using Pandas
Clean and preprocess data
Perform feature engineering
Split data using train_test_split
Train models:
Logistic Regression
Random Forest
Evaluate models using metrics

📊 Model Performance

Logistic Regression
Good baseline model
Performs well on linearly separable data
Random Forest Classifier
Higher accuracy compared to Logistic Regression
Handles non-linear relationships better
Reduces overfitting using ensemble learning

📈 Evaluation Metrics Used

Accuracy Score
Confusion Matrix
Precision, Recall, F1-score

📚 References

Scikit-learn Documentation: https://scikit-learn.org/stable/
Pandas Documentation: https://pandas.pydata.org/docs/
Kaggle Dataset: https://www.kaggle.com/datasets/shubhendra7/customer-churn-prediction

🔮 Future Improvements
Hyperparameter tuning (GridSearchCV / RandomSearchCV)
Try advanced models:
XGBoost
LightGBM
Handle class imbalance using SMOTE
Deploy model using Flask or Streamlit
Add feature importance visualization

✅ Conclusion

This project demonstrates how machine learning can be used to predict customer churn effectively. Among the models used, Random Forest performed better due to its ability to capture complex patterns.

Such models can help businesses take proactive steps to retain customers and reduce revenue loss.

