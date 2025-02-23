# Bank-Customer-Churn-Prediction
Project Overview
This project aims to predict bank customer churn using various machine learning models. By understanding the factors that lead to customer churn, banks can take proactive measures to enhance customer satisfaction and loyalty.

Dataset
The dataset used contains various features about bank customers, including their demographics, financial status, and engagement with the bank. The primary features in the dataset are:

CreditScore: The credit score of the customer.

Geography: The country where the customer resides.

Gender: The gender of the customer.

Age: The age of the customer.

Tenure: The number of years the customer has been with the bank.

Balance: The balance left in the customer's account.

NumOfProducts: The number of products the customer has with the bank.

HasCrCard: Whether the customer has a credit card.

IsActiveMember: Whether the customer is an active member.

EstimatedSalary: The estimated salary of the customer.

Exited: Whether the customer has churned (target variable).

Data Preprocessing
Exploratory Data Analysis (EDA): Understanding the dataset through visualizations like box plots, distribution plots, and pair plots.

Handling Missing Values and Encoding: Applying one-hot encoding to nominal features like Geography and Gender.

Addressing Class Imbalance: Using techniques like SMOTE to balance the classes in the training set.

Model Training
We experimented with several machine learning models to predict customer churn, including:

Logistic Regression

Support Vector Classifier (SVC)

K-Nearest Neighbors (KNN) Classifier

Decision Tree Classifier

Random Forest Classifier

Gradient Boosting Classifier

Model Evaluation
The performance of the models is assessed using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

Model Deployment
The best-performing model is saved and deployed using frameworks like FastAPI or Streamlit to provide a user-friendly web interface for real-time customer churn predictions.

Conclusion
This project demonstrates the effectiveness of machine learning techniques in predicting customer churn. Future improvements can include trying different models, tuning hyperparameters, and enhancing the user interface for better integration into production environments.

How to Run the Project
Install the required dependencies using pip install -r requirements.txt.

Run the Jupyter Notebook step by step.

Evaluate the model’s performance and make necessary modifications.

Acknowledgments
Special thanks to the open-source libraries Scikit-learn, XGBoost, and the web frameworks FastAPI and Streamlit for enabling efficient model building and deployment.
