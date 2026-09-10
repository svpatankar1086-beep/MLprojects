# Student Performance Analysis

A Machine Learning-based web application that analyzes how different student-related and educational factors are associated with student test performance.

## 📌 Project Overview

Student performance can be influenced by several factors such as gender, ethnicity, parental level of education, lunch type, test preparation, and academic scores.

This project uses Machine Learning and data analysis techniques to understand the relationship between these factors and student performance.

The project also provides a Flask-based web interface where users can enter student information and academic scores to obtain a model-based performance analysis.

---

## 🎯 Problem Statement

This project understands how the student's performance (test scores) is affected by other variables such as:

- Gender
- Ethnicity
- Parental level of education
- Lunch
- Test preparation course
- Reading score
- Writing score

The main objective is to analyze student performance using these different factors and demonstrate how Machine Learning can be integrated into a practical web application.

---

## 🚀 Features

- Student performance data analysis
- Exploratory Data Analysis (EDA)
- Data preprocessing and transformation
- Machine Learning model training
- Model evaluation
- Saved trained model using Pickle
- Flask-based web application
- User-friendly student data input form
- Model-based student performance analysis
- Modular Machine Learning project structure
- Separate training and prediction pipelines

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Machine Learning & Data Science
- NumPy
- Pandas
- Scikit-learn
- CatBoost

### Web Development
- Flask
- HTML
- CSS

### Development Tools
- Jupyter Notebook
- VS Code
- Git
- GitHub

---

## 📂 Project Structure

```text
MLproject/
│
├── artifacts/
│   ├── data.csv
│   ├── model.pkl
│   ├── proprocessor.pkl
│   ├── test.csv
│   └── train.csv
│
├── notebook/
│   ├── 1 . EDA STUDENT PERFORMANCE .ipynb
│   ├── 2. MODEL TRAINING.ipynb
│   └── data/
│       └── stud.csv
│
├── src/
│   ├── components/
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   └── model_trainer.py
│   │
│   ├── pipeline/
│   │   ├── predict_pipeline.py
│   │   └── train_pipeline.py
│   │
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
│
├── templates/
│   ├── home.html
│   └── index.html
│
├── app.py
├── requirements.txt
├── setup.py
├── .gitignore
└── README.md
