# Fraud_Detection_project
## Background
• Credit card fraud is the unauthorized use of a credit or debit card, or similar payment tool, to fraudulently obtain money or property. The purpose may be to obtain goods or services or to make payment to another account, which is controlled by a criminal

• There were nearly 400,000 reports of credit card fraud reported to the Federal Trade Commission last year, a number that grew 44% from 2019 to 2020. The key to minimizing the damage of this insidious crime is to detect it early and act immediately

## Dataset
• The sample Dataset summarizes the usage behavior of about 9000 active credit card holders during the last 10 months

• The data is at a customer level with 21 behavioral variables

## Goal
• Analyze and visualize credit card spending and paying data

• Build up a model to detect credit card fraud

## Data Description
• cust_id: Identification of Credit Card holder (Categorical)

• activated_date: The date customer activated their account

• last_payment_date: The date customer made their last payment

• balance: Balance amount left in their account to make purchases

• balance_frequency: How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)

• purchases: Amount of purchases made from account

• oneoff_purchases: Maximum purchase amount done in one-go

• insallments_purchases: Amount of purchase done in installment

• cash_advance: Cash in advance given by the user

• purchases_frequency: How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)

• oneoff_purchases_frequency: How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)

• purchases_insallments_frequency: How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)

• cash_advance_frequency: How frequently the cash in advance being paid

• cash_advance_trx: Number of Transactions made with "Cash in Advanced"

• purchases_trx: Number of purchase transactions made

• credit_limit: Limit of Credit Card for user

• payments: Amount of Payment done by user

• minimum_payments: Minimum amount of payments made by user

• prc_fullpayments: Percent of full payment paid by user

• tenure: Tenure of credit card service for user

• fraud: Identify if the customer is potentially fraud

## Built with
• Python, Pandas, Numpy, Seaborn, Matplotlib, Sklean

• Jupyter Notebook

## Procedures:
Data pre-processing and cleaning
Data exploration and visualiazation
Utilizing logistic regression to detect fraud
Measuring the performance of the model
