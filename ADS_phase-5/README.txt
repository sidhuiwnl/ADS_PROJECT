# Credit Card Fraud Detection

## Overview
This project focuses on developing a machine learning model for credit card fraud detection. 
The objective is to build a system that can identify and prevent fraudulent credit card 
transactions, minimizing financial losses for both financial institutions and customers.

## Dataset
- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Description:** The dataset contains credit card transaction data with 31 features, including time, 
transaction amount, and 28 anonymized features ('V1' to 'V28'). The target variable, 'Class,' indicates
 whether a transaction is fraudulent (1) or non-fraudulent (0).

## Requirements
- Python 3.x
- Required Libraries: 
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

Install the necessary libraries using the following command:
```bash
pip install -r requirements.txt

How to Run:

1.Download the Dataset:
	Download the dataset from the Kaggle dataset page.
	Save the dataset as 'creditcard.csv' in the project directory.
2.Run the Code:
	Open and run the 'credit_card_fraud_detection.py' script in your preferred Python environment (e.g., Jupyter Notebook or a code editor).

The script contains the following phases of the project:
	Data Preprocessing: Data cleaning, handling missing values, scaling features, and encoding categorical variables.	
	Feature Engineering: Creating new features to enhance fraud detection capabilities.
	Model Training: Training a Random Forest classifier for fraud detection.
	Model Evaluation: Evaluating the model's performance using precision, recall, F1-score, and ROC AUC.


Acknowledgments

We acknowledge the Kaggle community and contributors for providing the dataset used in this project.
 Special thanks to the scikit-learn and other open-source libraries for their valuable tools and resources.