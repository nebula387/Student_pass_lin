🎓 Student Exam Success Prediction
📌 Project Overview

This project focuses on analyzing factors that influence students’ exam success and building a machine learning model to predict whether a student will pass or fail an exam based on academic and behavioral features.

The task is formulated as a binary classification problem, where the target variable represents exam outcome (Pass / Fail).

📊 Dataset Description

The dataset contains anonymized student-level data with the following features:

student_id - id student

attendance_pct — class attendance percentage

homework_pct — homework performance score

midterm_score — midterm exam result

study_hours_per_week — weekly self-study hours

pass — final exam outcome (Pass / Fail)

🧠 Methodology
1. Exploratory Data Analysis (EDA)

Examined feature distributions and class balance

Analyzed relationships between features and exam outcomes

Computed Pearson correlations and statistical significance

2. Feature Engineering

Applied feature scaling using StandardScaler

3. Model Selection

Chosen model: Logistic Regression

Rationale:

Interpretable coefficients

Suitable for binary classification

Effective baseline model for structured tabular data

📈 Model Evaluation

The model was evaluated using the following metrics:

Precision & Recall — to assess classification performance

F1-score — balance between precision and recall

ROC-AUC — overall ability to distinguish between classes

The model demonstrated strong discriminative performance and stable generalization on test data.

🔍 Model Interpretation

Analysis of logistic regression coefficients revealed that the most influential features for exam success are:

Feature	Coefficient
Attendance percentage	1.46
Homework performance	1.42
Study hours per week	1.31
Midterm exam score	1.24

All key predictors show a positive impact on the probability of passing the exam.

✅ Key Findings

Attendance and homework performance are the strongest predictors of exam success

Midterm exam results provide an effective early signal of final outcomes

Logistic regression offers clear interpretability for educational insights

💡 Recommendations

Introduce early monitoring of attendance and homework performance

Identify students at risk before the final exam

Provide targeted academic support based on midterm results

Use the model as a decision-support tool rather than an automated system

🛠️ Tech Stack

Python

pandas, numpy

scikit-learn

scipy

🚀 Future Improvements

Compare with tree-based models (Random Forest, Gradient Boosting)

Perform cross-validation and hyperparameter tuning

Address potential class imbalance

Extend the analysis with additional behavioral features

📁 Repository Structure
├── data/
│   └── [student_pass](https://www.kaggle.com/datasets/ishanjha100/student-passfail-data)
├── notebooks/
│   └── ds_students_analysis.ipynb
├── src/
│   └── model.py
└── README.md

👤 Author

Snigirev Ivan
Aspiring Machine Learning Engineer / Data Analyst