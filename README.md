# Customer Churn Prediction

## 📋 Overview
This project predicts customer churn for a telecom company using **machine learning**. The goal is to identify customers likely to discontinue services so the business can proactively improve retention strategies.

## 🎯 Objectives
- Analyze customer demographics and usage patterns.
- Build predictive models to estimate churn probability.
- Identify the top features influencing customer retention.

## ⚙️ Tools & Technologies
- **Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost  
- **Environment:** Jupyter Notebook  

## 🧩 Workflow
1. **Data Cleaning** – Handle missing values, outliers, and encode categorical variables.  
2. **Exploratory Data Analysis (EDA)** – Visualize churn distribution, customer types, and feature correlations.  
3. **Feature Engineering** – Create new features and standardize numerical data.  
4. **Modeling** – Train multiple models (Logistic Regression, Random Forest, XGBoost).  
5. **Evaluation** – Compare performance using accuracy, recall, precision, F1-score, and ROC-AUC.  
6. **Insights** – Derive actionable recommendations to reduce churn.  

## 📊 Results
- Achieved **X% accuracy** and **Y% AUC** with the final XGBoost model.  
- Key churn indicators: short tenure, high monthly charges, month-to-month contracts.

## 🚀 Future Work
- Hyperparameter tuning and feature selection.
- Model deployment using Flask or Streamlit.
- Real-time churn prediction dashboard.

## 📁 Repository Structure
Customer-churn/
│

├── data/ # Raw and processed data

├── notebooks/ # Jupyter Notebooks (EDA, Model Training)

├── src/ # Python scripts

├── requirements.txt # Dependencies

└── README.md # Documentation

## 🏁 How to Run
1. Clone the repo  
   ```bash
   git clone https://github.com/swarada431/Customer-churn
   
2.Install dependencies

pip install -r requirements.txt

3.Run the notebook

jupyter notebook "Churn prediction.ipynb"

🙌 Acknowledgments

Dataset sourced from Kaggle – Telco Customer Churn
