# banking_clients_data
# Banking Customer Analysis

This project performs exploratory data analysis (EDA) on a banking dataset to understand customer behavior, financial attributes, and segmentations. The analysis is performed using Python in Jupyter Notebooks.

## 📁 Project Structure

├── banking.ipynb # Data preprocessing and initial analysis
├── BankEDA (Version 2) (1).ipynb # Advanced EDA and visualizations
├── Banking (2).csv # Input dataset containing banking customer information
└── README.md # Project overview and usage instructions

---

## 📊 Dataset Description

The dataset (`Banking (2).csv`) contains customer-level financial and demographic information such as:

- **Estimated Income**
- **Superannuation Savings**
- **Credit Card Balance**
- **Bank Loans**
- **Bank Deposits**
- **Checking Accounts**
- **Saving Accounts**
- **Foreign Currency Account**
- **Business Lending**
- **Properties Owned**
- **Risk Weighting**

## 🧪 Notebooks Overview

### 1. `banking.ipynb`
- Loads and inspects the dataset
- Handles missing values and data cleaning
- Generates initial statistics and distributions
- Identifies outliers

### 2. `BankEDA (Version 2) (1).ipynb`
- Provides in-depth analysis and visualizations
- Performs correlation and relationship analysis
- Includes feature engineering and grouping
- May contain business insights and actionable findings

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Plotly (optional)
- Scikit-learn (for preprocessing)

---

## 🚀 Getting Started

### Prerequisites

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn


Running the Notebooks
Clone or download the repository

Open the .ipynb files using Jupyter Notebook or JupyterLab

Run the cells sequentially

Customers with higher deposits tend to have lower loan balances.

Foreign currency account holders have above-average risk weighting.

Superannuation savings positively correlate with income.
