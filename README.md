# Data-Science-Intern-Assignment-Zeotap
# eCommerce Transactions Dataset - Data Science Assignment

## Overview

This project involves performing exploratory data analysis (EDA), building a lookalike model, and conducting customer segmentation using a provided eCommerce transactions dataset. The dataset consists of three files:

- **Customers.csv**: Customer details including ID, name, region, and signup date.
- **Products.csv**: Product information including ID, name, category, and price.
- **Transactions.csv**: Transaction records including customer ID, product ID, date, quantity, total value, and product price.

### Tasks Overview:

### Task 1: Exploratory Data Analysis (EDA) and Business Insights

1. **Perform exploratory data analysis (EDA)** on the dataset to identify key patterns and trends.
2. **Derive at least 5 actionable business insights** based on the EDA results. Insights should be concise (maximum 100 words per insight).

#### Deliverables:
- Jupyter Notebook/Python script containing the EDA code.
- PDF report with business insights (maximum 500 words).

### Task 2: Lookalike Model

1. **Build a Lookalike Model** that recommends 3 similar customers based on a user's profile and transaction history.
   - Use both customer and product information.
   - Assign a similarity score to each recommended customer.

#### Deliverables:
- List of top 3 lookalikes with similarity scores for the first 20 customers (CustomerID: C0001 - C0020).
- A CSV file `Lookalike.csv` with the format: `Map<cust_id, List<cust_id, score>>`.
- Jupyter Notebook/Python script explaining the model development.

### Task 3: Customer Segmentation / Clustering

1. **Perform customer segmentation** using clustering techniques with both profile and transaction data.
   - Choose any clustering algorithm and select the number of clusters (between 2 and 10).
   - Calculate clustering metrics, including the **DB Index**.
   - Visualize the clusters using appropriate plots.

#### Deliverables:
- Report on clustering results including:
  - Number of clusters formed.
  - DB Index value.
  - Other relevant clustering metrics.
- Jupyter Notebook/Python script containing the clustering code.

---

## Evaluation Criteria

- **Task 1**: EDA thoroughness and business insight quality.
- **Task 2**: Model accuracy, recommendation quality, and logic.
- **Task 3**: Clustering logic, evaluation metrics, and visualizations.

---

## Requirements

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Files Description

### 1. **Customers.csv**:
- `CustomerID`: Unique identifier for each customer.
- `CustomerName`: Name of the customer.
- `Region`: Continent where the customer resides.
- `SignupDate`: Date when the customer signed up.

### 2. **Products.csv**:
- `ProductID`: Unique identifier for each product.
- `ProductName`: Name of the product.
- `Category`: Product category.
- `Price`: Product price in USD.

### 3. **Transactions.csv**:
- `TransactionID`: Unique identifier for each transaction.
- `CustomerID`: ID of the customer who made the transaction.
- `ProductID`: ID of the product sold.
- `TransactionDate`: Date of the transaction.
- `Quantity`: Quantity of the product purchased.
- `TotalValue`: Total value of the transaction.
- `Price`: Price of the product sold.

---

## To Run the Code

1. Clone the repository to your local machine.
2. Install required libraries using `pip install -r requirements.txt`.
3. Open the Jupyter Notebook or Python script for each task to explore and run the code.
4. Execute the notebook cells in sequence to perform the analysis and modeling.


