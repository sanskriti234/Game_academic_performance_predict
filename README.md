# Gaming and Academic Performance Prediction

## Overview

This project uses Machine Learning to predict student academic performance based on gaming habits, study patterns, lifestyle, and behavioral factors.

The model analyzes how features such as gaming hours, study hours, sleep, attendance, stress level, and addiction score affect student grades.

---

## Features

* Data preprocessing using Scikit-Learn
* Categorical feature encoding
* Feature scaling using StandardScaler
* Linear Regression model
* Pipeline implementation
* Cross-validation for performance evaluation
* Model saving using Pickle

---

## Dataset Features

* Student Age
* Gender
* Gaming Hours
* Study Hours
* Sleep Hours
* Attendance
* Gaming Genre
* Social Activity
* Device Usage
* Reaction Time
* Addiction Score
* Stress Level

### Target Variable

* Grades

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Pickle

---

## Machine Learning Workflow

1. Load Dataset
2. Data Preprocessing
3. Encoding Categorical Features
4. Feature Scaling
5. Train-Test Split
6. Model Training using Linear Regression
7. Model Evaluation using R² Score
8. Save Trained Model

---

## Project Structure

```text
Gaming-Academic-Performance-Prediction/
│
├── Gaming_Academic_Performance.csv
├── analysis.ipynb
├── pipeline.ipynb
├── load.ipynb
├── pipe.pkl
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/sanskriti234/Game-academic-performance_predict.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run the Project

Open Jupyter Notebook and run the notebook file:

```bash
jupyter notebook
```


## Conclusion

This project demonstrates a complete Machine Learning pipeline for predicting student grades using gaming and lifestyle-related data. It is a beginner-friendly ML project that covers preprocessing, training, evaluation, and model saving.

---

## Author

Sanskriti Mishra
