# Bank-Customer-Churn-Prediction-Using-Artificial-Neural-Networks
![image alt](https://github.com/nilwagh8800/Bank-Customer-Churn-Prediction-Using-Artificial-Neural-Networks/blob/32d7752d62e16a4bcb663e9bf24af9130de9dab6/Screenshot%202025-02-24%20113515.png)

# Overview
This project is designed to predict customer churn using deep learning techniques. By analyzing key customer attributes such as demographic, financial, and account-related data, a deep neural network model provides accurate predictions on the likelihood of a customer leaving. The web application is built with Streamlit, offering an interactive interface where users can input customer details and receive instant predictions.

# Features

Deep Learning Model: A neural network model trained to predict churn based on customer data.

Real-Time Predictions: Users can enter customer details and get instant churn probability predictions.

Data Preprocessing: Includes scaling of numerical data and encoding of categorical features such as gender and geography.
User-Friendly Interface: Built with Streamlit, providing an easy-to-use form to input customer information.

Churn Probability: Displays the probability of churn and categorizes it as high or low risk.
Requirements

To run this project, you’ll need the following Python libraries:

streamlit

tensorflow

tensorboard

numpy

pandas

scikit-learn

pickle

Files in the Repository

app.py: The main Streamlit app that runs the interface and prediction logic.

model.h5: The pre-trained deep learning model saved in H5 format.

label_encoder_gender.pkl: Label encoder for the gender feature.

onehot_encoder_geo.pkl: One-hot encoder for the geography feature.

scaler.pkl: Standard scaler used to scale numerical data.

requirements.txt: List of dependencies required to run the project.

How It Works

Data Input: The user is prompted to input customer details such as geography, gender, age, balance, credit score, salary, tenure, and other relevant features.

Preprocessing: The input data is processed using the pre-loaded encoders and scaler. Categorical features are encoded, and numerical data is scaled.

Prediction: The preprocessed data is passed through the deep learning model to predict the likelihood of churn.

Result: A probability value is displayed, indicating the likelihood of the customer churning, along with a visual indication (green for low risk, red for high risk).
