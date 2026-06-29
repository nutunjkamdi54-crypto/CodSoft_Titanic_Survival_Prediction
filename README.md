# 🚢 Titanic Survival Prediction

## 📌 Project Overview
This project predicts whether a passenger survived the Titanic disaster using Machine Learning algorithms. It involves data preprocessing, visualization, feature engineering, model training, evaluation, and comparison of multiple classification models.

## 🎯 Objective
Build a machine learning model that predicts passenger survival based on features like:
- Passenger Class
- Gender
- Age
- Fare
- Number of Siblings/Spouses
- Number of Parents/Children
- Embarkation Port

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## 📊 Dataset
The dataset is from the Kaggle Titanic: Machine Learning from Disaster competition.

Training Data: 891 records

Testing Data: 418 records

## 🔍 Data Preprocessing
- Handled missing values
- Removed Cabin column
- Filled Age using Median
- Filled Embarked using Mode
- Converted categorical features using Label Encoding

## 🤖 Machine Learning Models
- Logistic Regression
- Decision Tree
- Random Forest ⭐ (Best Model)
- K-Nearest Neighbors (KNN)

## 📈 Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | ~81% |
| Decision Tree | ~78% |
| Random Forest | ~82% |
| KNN | ~72% |

## 📊 Visualizations
- Survival Count
- Survival by Gender
- Survival by Passenger Class
- Confusion Matrix
- Model Comparison Chart
- Feature Importance

## 💾 Saved Model
The best-performing Random Forest model is saved using Joblib.

## 📁 Project Structure

text
Titanic-Survival-Prediction/
│
├── dataset/
│   ├── train.csv
│   └── test.csv
│
├── notebook/
│   └── Titanic_Survival.ipynb
│
├── models/
│   └── random_forest_model.pkl
│
├── images/
├── requirements.txt
└── README.md

## 👨‍💻 Author
**Nutunj Kamdi**

CodSoft Data Science Internship
