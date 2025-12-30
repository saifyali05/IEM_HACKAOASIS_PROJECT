# Fraud-Detection-System
This project uses machine learning to detect fraud in data. It analyzes patterns and classifies whether a it is genuine or fraudulent.
This project was made by our team syntax squad in Hackoasis2K25 held in IEM.
📌 Project Overview

This Fraud Detection System demonstrates a complete machine-learning pipeline — from data preprocessing and exploration to model training, evaluation, and prediction.
It is designed to be simple, scalable, and extendable for real-world fraud-detection use cases.

# 🚀 Features

Data cleaning and preprocessing

Exploratory Data Analysis (EDA)

Class imbalance handling (SMOTE / undersampling)

Machine learning model training

Fraud vs Non-Fraud classification

Performance evaluation (Accuracy, Precision, Recall, F1-Score, ROC-AUC)

Easy to extend for production-level systems

Folder Structure
```
IEM_HACKAOASIS_PROJECT/
├── .idea/
├── __pycache__/
├── dashboard/
├── data/
├── models/
├── notebooks/
├── results/combined_results/
├── src/
├── .gitattributes
├── README.md
├── api.py
├── requirements.txt
├── run.sh
└── yolov8n.pt

```
# 🧠 Machine Learning Workflow
Load & Clean Data

Handle missing values

Normalize / scale numerical features

Exploratory Data Analysis (EDA)

Identify fraud vs non-fraud distribution

Visualize patterns and correlations

Handle Class Imbalance

Use SMOTE or undersampling

Model Training

Logistic Regression

Random Forest

XGBoost

Model Evaluation

Confusion Matrix

Accuracy, Precision, Recall, F1-Score

ROC-AUC Curve

Prediction

Classify new transactions as Fraudulent or Legitimate
# To Clone
```
git clone https://github.com/saifyali05/Fraud-Detection-System
cd Fraud-Detection-System
pip install -r requirements.txt
```
# 📈 Future Improvements
Add deep-learning models (LSTM, Neural Networks)

Build a Flask / FastAPI backend

Implement real-time fraud detection using Kafka

Deploy using AWS (EC2 / Lambda) or Docker

🤝 Contributing
Contributions are welcome!
Feel free to open issues or submit pull requests to improve the system.

⭐ Support
If you find this project useful, don’t forget to give it a star ⭐ on GitHub!

