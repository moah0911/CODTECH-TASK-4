# CODTECH-TASK-4


---

# Spam Email Detection using Multinomial Naive Bayes

This project is a task from CODTECH, demonstrating the implementation of a predictive model to classify emails as spam or not spam. It uses a dataset containing numerical features derived from email content, along with corresponding labels indicating whether an email is spam.

## Features

- **Data Preprocessing**: Cleans and prepares the dataset by removing unnecessary columns and splitting it into training and testing sets.
- **Machine Learning Model**: Utilizes the Multinomial Naive Bayes algorithm for classification.
- **Evaluation**: Assesses the model's performance with accuracy scores and a detailed classification report.
- **Example Prediction**: Includes a mechanism to test the model on custom inputs.

## Requirements

- Python 3.7+
- Required Libraries: `pandas`, `scikit-learn`

## Dataset

The dataset is provided by CODTECH and contains:
- **Features**: Numerical representations of email text.
- **Target**: A `Prediction` column (1 for spam, 0 for not spam).

## How to Run

1. Clone this repository and navigate to the project directory.
2. Ensure the dataset file is located at the specified path: `C:\Users\gowth\hello\python projects\CODTECH\emails`.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the script in your preferred Python environment (e.g., Jupyter Notebook or terminal):
   ```bash
   python spam_email_detection.py
   ```
5. Review the model’s performance metrics and test it with example inputs.
