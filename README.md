# Employee-Turnover-Prediction-using-Machine-Learning

#### Logistic Regression | Classification Project

##### 📌 Project Overview

This project focuses on predicting employee attrition (turnover) using Machine Learning.

A multinational company (TalentCore Pvt. Ltd.) is experiencing a high number of employee resignations, leading to increased recruitment costs and productivity loss.

👉 The goal is to build an intelligent ML system that can predict whether an employee is likely to leave the company based on various factors like job satisfaction, salary, work-life balance, etc.

##### 🎯 Objectives
Build a baseline Logistic Regression model
Improve performance using Regularization (L1 & L2)
Compare models and recommend the best-performing model

##### 📊 Dataset Description

The dataset contains ~900 rows and 15+ features, representing employee-related information.

🔑 Key Features:

| Feature                    | Description                 |
| -------------------------- | --------------------------- |
| Job_Satisfaction           | Job satisfaction level      |
| Performance_Rating         | Employee performance score  |
| Years_At_Company           | Years worked in the company |
| Work_Life_Balance          | Work-life balance rating    |
| Distance_From_Home         | Distance to workplace       |
| Monthly_Income             | Salary of employee          |
| Education_Level            | Education qualification     |
| Age                        | Age of employee             |
| Num_Companies_Worked       | Previous companies worked   |
| Employee_Role              | Encoded job role            |
| Department                 | Encoded department          |
| Annual_Bonus               | Bonus received annually     |
| Training_Hours             | Training hours attended     |
| Annual_Bonus_Squared       | Engineered feature (bonus²) |
| Bonus_Training_Interaction | Interaction feature         |

#### 🧹 Data Preprocessing

✔ Handled missing values
✔ Encoded categorical variables
✔ Feature scaling (if required)
✔ Removed inconsistencies
✔ Created new engineered features

##### ⚙️ Model Building
🔹 Baseline Model
Logistic Regression (without regularization)
🔹 Improved Models
L1 Regularization (Lasso)
L2 Regularization (Ridge)
🔹 Model Comparison

Compared models based on performance metrics to select the best one.

##### 📈 Model Evaluation

The models were evaluated using:

Accuracy
Precision
Recall
F1 Score
ROC-AUC Curve

📌 Regularization helped reduce overfitting and improved generalization.

##### 🔍 Key Insights

📉 Low job satisfaction increases attrition probability
⚖️ Poor work-life balance leads to higher turnover
💰 Higher income and bonuses improve retention
📚 Training hours positively impact employee engagement
🧠 Feature engineering improved model performance

#### 🛠 Tech Stack
Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

#### 🏁 Conclusion

This project demonstrates how Machine Learning can help HR teams predict employee attrition, enabling proactive decision-making and improving employee retention strategies.
