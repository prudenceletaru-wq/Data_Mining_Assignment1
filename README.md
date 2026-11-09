DSC8307 - Assignment 1: Data Mining, Modeling and Analytics
This repository contains the Jupyter Notebooks and dependencies for the Project-Based Assignment.

Repository Contents
project1_bank_marketing.ipynb: A binary classification pipeline designed to predict whether a bank client will subscribe to a term deposit. It includes exploratory data analysis, target leakage removal, hyperparameter tuning (Logistic Regression, Random Forest, XGBoost), and a business-driven decision threshold analysis.

project2_concrete.ipynb: A regression pipeline designed to predict concrete compressive strength based on mixture ingredients. It includes VIF multicollinearity analysis, comparison of linear vs. non-linear models, and residual diagnostics.

requirements.txt: The list of Python dependencies required to run the notebooks.

bank-additional-full.csv: The dataset for Project 1.

Concrete_Data.csv: The dataset for Project 2.

Setup and Execution Instructions
To reproduce the results, please follow these steps:

Clone the repository to your local machine.

Install the required dependencies by running:

pip install -r requirements.txt

Run the Notebooks:
Launch Jupyter Notebook or Jupyter Lab from your terminal by running:

jupyter notebook

Open either .ipynb file and run the cells from top to bottom (Kernel -> Restart & Run All).

Note: The datasets are located in the root directory alongside the notebooks; therefore, no folder restructuring is required. All random states are fixed (e.g., random_state=42) to guarantee reproducibility.