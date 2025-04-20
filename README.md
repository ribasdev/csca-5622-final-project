# 🫀 Heart Disease Prediction using Supervised Learning

This project uses various supervised learning algorithms to predict whether a patient has heart disease based on clinical parameters. It leverages the UCI Heart Disease dataset and compares models such as Logistic Regression, Decision Trees, Random Forest, and SVM.

## 📌 Problem Statement

Cardiovascular diseases are the leading cause of death globally. This project aims to use machine learning to detect potential heart disease in patients based on features such as age, cholesterol, resting blood pressure, chest pain type, and others.

---

## 🧠 ML Techniques Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- Evaluation with accuracy, precision, recall, F1-score, and ROC AUC

---

## 📂 Dataset

- Source: [UCI Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- Alternatively used:  
  [`https://raw.githubusercontent.com/sharmaroshan/Heart-UCI-Dataset/master/heart.csv`](https://raw.githubusercontent.com/sharmaroshan/Heart-UCI-Dataset/master/heart.csv)

---

## ✅ Results Summary

The best-performing model was:
- **Random Forest Classifier**  
- **Accuracy**: ~87%  
- **ROC AUC**: ~0.91

---

## 🛠️ Setup Instructions

### 1. Clone this repository

```bash
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
```

### 2. Set up a Python virtual environment (Recommended: Python 3.11.9)

```bash
python3.11 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

> **Note**: If `requirements.txt` is missing, install manually with:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## 🚀 Run the Project

```bash
jupyter notebook supervised_learning_project.ipynb
```

---

## 📊 Example Outputs

- Confusion matrix
- Classification report
- ROC curve
- Model comparisons

---

## 📌 Author

Leonardo Ribas

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
