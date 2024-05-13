# Loan Default Prediction

## Overview

This project aims to predict loan defaults using machine learning techniques. The dataset comprises historical loan data, including various borrower attributes and loan characteristics. The goal is to build a predictive model that can accurately identify borrowers who are likely to default on their loans.

## Features

- **Data Preprocessing:** Includes data cleaning, feature engineering, and handling missing values to prepare the dataset for modeling.
- **Modeling:** Utilizes various machine learning algorithms such as [list algorithms you used, e.g., ADABoost, Random Forest, KNN, etc.] for loan default prediction.
- **Evaluation:** Evaluates model performance using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
- **Visualization:** Provides visualizations of loan data distribution, model performance metrics, and feature importance.
- **Outliers:** Uses BoxPlot and the standard deviation technique of `mean +- 2*(std)` for filtering out outliers.
- **SMOTE:** Used this technique for oversampling the minority data synthetically since the dataset is class imbalanced.
- **Hypertuning:** Performed this in best performing algorithm obtained from the forward selection technique.
- **MonteCarlo:** Used this MonteCarlo way of replacing the NaN in the dataset for accurate predictions.

## Usage

### Prerequisites

- Python 3.x
- Required Python packages listed in `requirements.txt`

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your_username/loan-default-prediction.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd loan-default-prediction
    ```

3. **Install required packages:**

    ```bash
    pip install -r requirements.txt
    ```

### Running the Code

1. **Run the Jupyter Notebook:**

    ```bash
    loan_default_prediction.ipynb
    ```


## Results

[Achieved overall accuracy of 84% after using the forward selection technique]


