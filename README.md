# Credit Risk Prediction using XGBoost
A machine learning–based credit risk prediction system using XGBoost, deployed as an interactive Streamlit web application to classify applicants as Good or Bad credit risk.

This project is a machine learning–based Credit Risk Prediction system that classifies loan applicants as Good or Bad credit risk.
Multiple classification models were evaluated, and XGBoost (XGB) was selected as the final model due to its superior performance.

The trained model is deployed using a Streamlit web application, allowing users to interactively enter applicant details and receive real-time predictions.

🚀 Features
1.Predicts Good / Bad Credit Risk
2.Uses XGBoost, the best-performing model among tested algorithms
3.Interactive Streamlit web interface
4.Handles categorical features using label encoding
5.Real-time predictions with a trained ML model

Machine Learning Approach
Models Evaluated
Several machine learning algorithms were trained and evaluated during experimentation, including:
Decision Tree
Random Forest
Extra Trees Classifier
XGBoost

XGBoost was chosen as the final model because it provided:

Higher predictive accuracy
Better handling of non-linear relationships
Robust performance compared to other models

Prediction Output

The model classifies applicants into two categories:

Prediction	Meaning
Good Credit Risk	-->Low likelihood of loan default
Bad Credit Risk -->	Higher likelihood of loan default

🖥 Web Application

The Streamlit app allows users to input the following details:

Age
Sex
Job type
Housing status
Saving account status
Checking account status
Credit amount
Loan duration (months)

Based on these inputs, the trained XGBoost model predicts the applicant’s credit risk.

🛠️ Tech Stack

Python
Pandas
Scikit-learn
XGBoost
Streamlit
Joblib

Dataset

The dataset contains applicant demographic and financial information such as age, employment status, housing, account balances, credit amount, and loan duration.

Note: This project is intended for educational and demonstration purposes only and should not be used for real-world financial decision-making without proper validation.

📈 Future Improvements

Add feature importance visualization
Display model confidence/probability
Improve UI/UX with charts and explanations
Deploy the app on Streamlit Cloud or other platforms

👨‍💻 Author
Sanmitra Kamble
