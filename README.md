# Employee-Attrition-Prediction-using-ML-tools

## 📌 Overview

This project aims to predict whether an employee will leave the company (attrition) using Machine Learning techniques. Employee attrition is a critical issue for organizations due to its impact on performance, cost, and morale. With the help of HR analytics, we can identify key factors contributing to attrition and take proactive steps to improve retention.

---

## 📂 Dataset

- **Source**: [IBM HR Analytics Employee Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Size**: ~1.5 MB, 1470 rows, 35 columns
- **Target Variable**: `Attrition` (Yes / No)

---

## 💻 Tech Stack

- Python 🐍
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab (for development)

---

## 📊 Workflow

### 1. Problem Definition
Understanding why employee attrition happens and why predicting it is important for HR decision-making.

### 2. Data Exploration
- Viewing data structure
- Checking for missing values
- Basic statistical summary

### 3. Data Preprocessing
- Label encoding of categorical variables
- Feature selection
- Data normalization (if needed)
- Splitting data into train/test sets

### 4. Exploratory Data Analysis (EDA)
- Correlation heatmaps
- Distribution of key variables
- Attrition rates by department, gender, job role, etc.

### 5. Model Building
Trained multiple ML models such as:
- Logistic Regression
- Random Forest
- Decision Tree
- Support Vector Machine (SVM)

### 6. Evaluation
- Accuracy
- Confusion Matrix
- Precision, Recall, F1-score
- ROC-AUC (if implemented)

### 7. Insights & Conclusion
- Identified top features influencing attrition
- Discussed key business takeaways

---

## 📈 Results

| Model              | Accuracy | F1 Score |
|-------------------|----------|----------|
| Logistic Regression | 85%      | 0.78     |
| Random Forest       | 88%      | 0.81     |
| SVM                 | 86%      | 0.79     |

> *(Values above are for example only — replace them with your actual results)*

---

## 🚀 How to Run

### Option 1: Run in Google Colab
1. Upload the notebook.
2. Upload the dataset manually.
3. Run all cells in order.

### Option 2: Local Machine
```bash
git clone https://github.com/yourusername/employee-attrition-prediction.git
cd employee-attrition-prediction
pip install -r requirements.txt
jupyter notebook
