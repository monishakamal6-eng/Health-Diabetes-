🩺 Health – Diabetes Prediction

📌 Project Overview

This project uses Machine Learning to predict whether a person may have diabetes based on health-related information.

The dataset contains 70,692 health survey records with 22 columns. Important features include BMI, Age, High Blood Pressure, High Cholesterol, Physical Activity, General Health and Income.

🎯 Objective

The main objective is to build a Machine Learning model that can help predict diabetes risk using health data.

📊 Dataset

- Records: 70,692
- Columns: 22
- Target: "Diabetes_binary"
- Duplicate records removed: 1,635
- Missing values: None

After cleaning, the dataset contained 69,057 records.

🔍 Exploratory Data Analysis

The following analysis was performed:

- Checked missing values and duplicates
- Studied BMI and Age distributions
- Created box plots and count plots
- Analyzed correlations between features
- Identified important features related to diabetes

🤖 Machine Learning Algorithms

Three algorithms were used:

1. Logistic Regression
2. Decision Tree
3. Random Forest

Model Accuracy

Algorithm| Accuracy
Logistic Regression| 74.50%
Decision Tree| 73.16%
Random Forest| 72.99%

Best model: Logistic Regression – 74.50% accuracy

📈 Evaluation Metrics

The models were evaluated using:

- Accuracy – Overall correct predictions
- Precision – Correctness of positive predictions
- Recall – Ability to identify actual positive cases
- F1 Score – Balance between Precision and Recall

The Random Forest top-10 feature model achieved approximately 71% accuracy with an AUC of 0.776.

⭐ Important Features

Some important features identified were:

- BMI
- Age
- General Health
- Income
- High Blood Pressure
- Physical Health
- Education
- Mental Health
- High Cholesterol
- Fruits

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

📁 Project Structure

Health-Diabetes-Prediction/
│
├── health.csv
├── Health_Diabetes_Prediction.ipynb
├── README.md
└── PPT/
    └── Health PPT PRESENTATION.pptx

📌 Conclusion

This project demonstrates how Machine Learning can be used to predict diabetes risk from health data.

Logistic Regression achieved the highest accuracy of 74.50% among the tested models.

«⚠️ This project is intended as a screening/research aid and not a medical diagnosis tool.»

👩‍💻 Author

K. Monisha
BCA Final Year Student
Interested in UI/UX Design, Figma, Prototyping and Wireframing
