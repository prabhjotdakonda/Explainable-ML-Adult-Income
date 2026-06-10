# Explainable AI on Adult Income Dataset

## 📌 Project Overview
This project demonstrates an Explainable Machine Learning pipeline built on the Adult Income Dataset. The goal is not only to predict income levels but also to make the model decisions transparent using Explainable AI (XAI) techniques such as SHAP and LIME.

The project focuses on understanding:
- Which features influence predictions the most
- How the model reaches a decision
- Fairness, bias, and interpretability in machine learning models

---

## 🎯 Objectives
- Build a classification model to predict income (>50K or ≤50K)
- Preprocess real-world messy data
- Train and evaluate machine learning models
- Apply explainability techniques:
  - SHAP (SHapley Additive exPlanations)
  - LIME (Local Interpretable Model-Agnostic Explanations)
- Analyze feature importance and model behavior
- Study fairness and bias in predictions

---

## 📊 Dataset
- Name: Adult Income Dataset  
- Source: UCI Machine Learning Repository  
- Files used:
  - adult.data → Training data
  - adult.test → Testing data

### Features include:
- Age
- Workclass
- Education
- Occupation
- Hours per week
- Capital gain/loss
- Marital status
- etc.

Target variable:
- Income class: <=50K or >50K

---

## ⚙️ Data Preprocessing
- Replaced '?' with NaN
- Missing categorical values handled using mode imputation
- Encoded categorical variables
- Scaled numerical features (if required)
- Split dataset into training and testing sets

---

## 🤖 Model Used
- Decision Tree Classifier (or your final selected model)
- Trained on processed dataset
- Evaluated on test data

### Evaluation Metrics:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 🔍 Explainability Methods

### SHAP (Global Explanation)
- Explains overall feature importance
- Shows how each feature contributes to predictions
- Used SHAP summary plots for interpretation

### LIME (Local Explanation)
- Explains individual predictions
- Shows why a specific prediction was made
- Helps understand model behavior for single samples

---

## 📈 Key Insights
- Features like education, occupation, and capital gain are highly influential
- Model shows clear patterns in decision-making
- SHAP confirms global feature importance
- LIME provides clear local explanations

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- SHAP
- LIME
