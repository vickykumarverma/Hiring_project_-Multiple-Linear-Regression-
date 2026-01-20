# Hiring_project_-Multiple-Linear-Regression-
Hiring_project_(Multiple Linear Regression)


Hiring Prediction Project
📌 Project Overview

This project demonstrates a machine learning–based hiring salary prediction system using Python.
The model predicts an employee’s expected salary based on factors such as:

Years of experience

Test score

Interview score

The project is implemented in a Jupyter Notebook and focuses on data preprocessing, feature engineering, and regression modeling.

🛠️ Technologies Used

Python

Jupyter Notebook

Pandas

NumPy

Scikit-learn

word2number

📂 Project Structure
Hiring_Project/
│
├── Hiring_Project.ipynb   # Main Jupyter Notebook
├── README.md              # Project documentation

📊 Dataset Description

The dataset includes the following columns:

Column Name	Description
experience	Years of experience (numeric / text-based)
test_score	Score obtained in test
interview_score	Score obtained in interview
salary	Final salary offered (target variable)

Missing values and text-based numbers are handled during preprocessing.

🔄 Data Preprocessing

Converted textual numbers (e.g., "two", "five") into numeric values

Handled missing values using appropriate imputation techniques

Ensured all features are numerical for model training

🤖 Machine Learning Model

Algorithm Used: Linear Regression

Library: scikit-learn

Objective: Predict salary based on candidate evaluation metrics

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/your-username/Hiring_Project.git


Navigate to the project directory:

cd Hiring_Project


Open Jupyter Notebook:

jupyter notebook


Run Hiring_Project.ipynb cell by cell

📈 Output

The model predicts salary values based on user-provided inputs for:

Experience

Test score

Interview score

🎯 Use Cases

Beginner-friendly machine learning project

Academic mini project

Interview preparation (ML fundamentals)

Regression model demonstration

🚀 Future Improvements

Use larger real-world datasets

Add feature scaling and model evaluation metrics

Compare multiple regression models

Deploy using Flask or Streamlit

📄 License

This project is open-source and available for educational use.
