# Employee Burnout Prediction

A machine learning project that predicts the likelihood of employee burnout based on various workplace and personal factors. This tool can assist organizations in identifying at-risk employees early and taking proactive measures to improve employee well-being and productivity.

## 🔍 Problem Statement

Burnout in the workplace is a critical issue that affects both employees and employers. By analyzing relevant data, this project aims to build a predictive model that can identify signs of burnout using supervised learning techniques.

## 📊 Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Model training using various classification algorithms
- Accuracy and performance evaluation
- Flask-based web interface for real-time prediction

## 📁 Project Structure

Employee_Burnout_Prediction/
│
├── templates/ # HTML files for the web interface
├── static/ # CSS or images (if used in UI)
├── model/ # Saved ML model (e.g., .pkl file)
├── app.py # Flask application
├── burnout_predictor.ipynb # Jupyter Notebook for analysis & training
├── requirements.txt # List of required Python packages
└── README.md # Project documentation


## 🛠️ Tech Stack

- Python
- Pandas, NumPy, Scikit-learn
- Matplotlib, Seaborn (for EDA)
- Flask (for deployment)

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/ramakrishnakola507/Employee_Burnout_Prediction.git
2. Navigate to the project directory:
   cd Employee_Burnout_Prediction
3. Install the required packages:
   pip install -r requirements.txt
4. Run the Flask application:
   python app.py
5. Open your browser and go to http://localhost:5000

📈 Model Used
Trained using Scikit-learn classifiers such as:

Logistic Regression

Random Forest

Support Vector Machines (SVM)

Model performance is evaluated using accuracy, precision, recall, and F1-score.

📌 Purpose
This project was developed as part of a machine learning internship to demonstrate the application of data science and web deployment in solving real-world problems.
