# 🫀 Heart Disease Prediction using Machine Learning

This project applies machine learning techniques to predict the presence of heart disease based on patient medical attributes.

## 🧠 Project Overview

The goal is to build and evaluate a classification model that can predict whether a patient has heart disease using clinical features such as age, cholesterol level, chest pain type, etc.

## 🧪 Project Structure

The notebook follows these steps:

1. **Problem Definition**

   > Can we predict the presence of heart disease given clinical parameters?

2. **Data Source**

   * UCI Machine Learning Repository: [Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
   * [Kaggle version](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset)

3. **Evaluation Metric**

   * Achieve at least **95% accuracy** in predicting heart disease during proof of concept.

4. **Features**
   A range of clinical attributes like:

   * `age`, `sex`, `cp`, `chol`, `thalach`, etc.
   * `target`: 1 = disease present, 0 = no disease

5. **Modeling**
   Algorithms used:

   * Logistic Regression
   * K-Nearest Neighbors
   * Random Forest

6. **Experimentation**
   Includes hyperparameter tuning and cross-validation to improve performance.

## 📁 File Structure

```
├── heart-disease.ipynb          # Main Jupyter notebook
├── data/
│   └── heart-disease.csv        # Dataset file
├── requirements.txt             # Python dependencies
└── README.md                    # Project documentation
```

## ⚙️ Installation

To run this project, clone the repo and install dependencies:

```bash
git clone https://github.com/ridamansour/heart-disease-predictor.git
cd heart-disease-predictor
pip install -r requirements.txt
```

## 🚀 How to Run

```bash
jupyter notebook heart-disease.ipynb
```

Ensure that `data/heart-disease.csv` exists in the `data/` folder before running.

## 🛠 Tools & Libraries

* Python, NumPy, Pandas
* Matplotlib, Seaborn
* scikit-learn

## 📊 Example Output

The notebook generates confusion matrices, ROC curves, and other metrics for performance evaluation.

## 📌 Goals

* Demonstrate effective use of scikit-learn
* Practice hyperparameter tuning and model evaluation
* Provide educational insight into medical ML modeling

## 🧾 License

This project is open-source.
