# medical-billing-analyzer

This project provides a script for loading, summarizing, and identifying discrepancies in medical billing data. The script reads data from a CSV file, calculates the total billing amount, and identifies potential discrepancies based on billing values.

# Features
Data Loading: Loads medical billing data from a CSV file.
Billing Summary: Calculates and displays the total amount billed.
Discrepancy Detection: Identifies discrepancies where the billing amount is greater than zero, assuming that these indicate unusual or erroneous entries.


# Requirements
Python 3.x
Packages: pandas
You can install the required packages with:

pip install pandas
Usage
1. Clone the repository or download the script file.

2. Run the script in your terminal:
python main.py
3. When prompted, enter the path to your medical billing CSV file (e.g., data/billing_data.csv).

# Functions
load_data(file_path): Loads data from the specified CSV file, printing column names to verify structure.
summarize_billing(data): Summarizes the total billed amount.
find_discrepancies(data): Identifies records with discrepancies in billing.

# Error Handling
The script includes error handling for missing files or columns, ensuring smooth execution even with incomplete data.
