Credit Scoring Model

Project Overview
This project is developed as part of the "CodeAlpha Machine Learning Internship".

The objective of this project is to build a "Credit Scoring Model" that predicts whether a customer is likely to be creditworthy based on their financial and loan-related information. The project applies multiple machine learning classification algorithms and compares their performance using standard evaluation metrics.


 Objective

- Predict customer creditworthiness using machine learning.
- Perform data preprocessing and feature engineering.
- Train and compare multiple classification algorithms.
- Evaluate model performance using different metrics.


Dataset

The dataset contains customer loan and financial information such as:

- Loan Amount
- Funded Amount
- Interest Rate
- Employment Duration
- Home Ownership
- Verification Status
- Payment Plan
- Debt-to-Income Ratio
- Credit History
- Loan Title
- Loan Status (Target Variable)

Target Variable:
- Loan Status
  - 1 = Good Credit
  - 0 = Bad Credit

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

Data Preprocessing

The following preprocessing steps were performed:

- Handling missing values
- Encoding categorical features
- Feature engineering
- Removing unnecessary columns
- Splitting features and target variable

Machine Learning Algorithms

The following classification algorithms were implemented:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

Model Comparison

The performance of all three models was compared to determine the best-performing algorithm for credit scoring.

Project Structure

CodeAlpha_CreditScoringModel/
│
├── Credit_Scoring_Model.ipynb
├── train.csv
├── test.csv
├── README.md
├── requirements.txt
└── images/


 ▶ How to Run

1. Clone the repository


git clone https://github.com/yourusername/CodeAlpha_CreditScoringModel.git


2. Install dependencies


pip install -r requirements.txt

3. Open the Jupyter Notebook or Google Colab.

4. Run all cells from top to bottom.

Results

Three machine learning classification models were trained and evaluated.

The evaluation metrics (Accuracy, Precision, Recall, F1-Score, and ROC-AUC) were used to compare model performance. The best-performing model can be selected based on these results.

 Internship

This project was completed as part of the "CodeAlpha Machine Learning Internship".


Author

Tasmia Mughal

