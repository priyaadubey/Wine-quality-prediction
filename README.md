# Wine Quality Prediction using Machine Learning 🍷

This project predicts the quality of red wine based on various chemical properties using machine learning models.

## 🔍 Project Overview
- Conducted **Exploratory Data Analysis (EDA)** and feature engineering.
- Used **Logistic Regression, Random Forest and Gradient Boosting** models.
- **Random Forest** achieved the best accuracy: **70%**.
- Key influencing factors: **Alcohol, Sulphates, Volatile Acidity**.
- Model performs well for mid-range wines (quality 5 & 6) but struggles with extreme cases.

## 🚀 Technologies Used
- **Python**
- **Pandas, NumPy, Matplotlib, Seaborn**
- **Scikit-Learn** (for ML models)
- **Hyperparameter Tuning** with GridSearchCV

## 📊 Results & Future Improvements
- Improved performance with **Hyperparameter Tuning**.
- Can enhance recall for poor-quality wines using **class balancing techniques**.

## 🔧 Installation
To run the project, install the required dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn