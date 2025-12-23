# Premier League Match Score Prediction System

This project is an end-to-end machine learning application designed to predict English Premier League match scores using historical match data. It combines data analytics, machine learning, and interactive web deployment to deliver real-time score predictions through a user-friendly interface.

# Machine Learning Pipeline

1. Performed data cleaning, preprocessing, and exploratory data analysis (EDA)

2. Engineered match-level features, including team matchups and home/away advantage

3. Experimented with multiple regression models and optimized performance using XGBoost

4. Evaluated models using industry-standard metrics: MAE, MSE, RMSE, and R²

5. Selected and serialized the best-performing model for production use

# Model Serialization & Reusability

1. Trained the model in a Jupyter Notebook (model.ipynb)

2. Converted the final optimized model into a reusable model.pkl file using Python’s pickle

3. Ensured efficient inference during deployment without retraining the model

# Interactive Web Application (Streamlit)

1. Developed an interactive Streamlit web app for real-time match score prediction

2. Enabled users to:

    - Select competing Premier League teams

    - Apply a home/away match filter

    - Generate score predictions with a single click

    - Designed the interface for simplicity, clarity, and accessibility