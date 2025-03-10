# Credit Card Fraud Detection
# Dataset link:- https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
## Overview
This project implements a **Credit Card Fraud Detection** system using **Logistic Regression**. The dataset used contains transactions labeled as fraudulent or legitimate, and the model is trained to classify them accurately.

## Dataset
The dataset used is `creditcard.csv`, which includes transaction features and a `Class` label:
- **0**: Legitimate transaction
- **1**: Fraudulent transaction

## Steps Involved
1. **Import Dependencies**: Libraries such as NumPy, Pandas, and Scikit-Learn are used.
2. **Load Dataset**: The dataset is loaded and explored using `pandas`.
3. **Data Preprocessing**:
   - Handle missing values (if any).
   - Analyze class distribution (highly imbalanced dataset).
   - Extract statistical insights.
4. **Data Balancing**:
   - Use undersampling techniques to balance fraud and non-fraud transactions.
5. **Model Training**:
   - Train a **Logistic Regression** model using `train_test_split`.
6. **Evaluation**:
   - Use **accuracy score** and other relevant metrics to assess the model performance.

## Technologies Used
- Python
- NumPy & Pandas
- Scikit-Learn
- Google Colab

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/narsingChinna/credit-card-fraud-detection.git
   ```
2. Navigate to the project directory:
   ```bash
   cd credit-card-fraud-detection
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook or script:
   ```bash
   jupyter notebook
   ```
5. Execute the notebook step by step.

## Future Enhancements
- Implement **Random Forest, XGBoost, and Deep Learning** for improved accuracy.
- Use **SMOTE** to handle class imbalance.
- Deploy the model using Flask or FastAPI.

