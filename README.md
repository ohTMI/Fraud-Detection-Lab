# Financial Fruad Detection

# Project Overview

In this project, we're working with a considerably large dataset of financial transactions, aiming to detect and flag fraudulent transaction while trying to filter out falsfe positives. Class imbalance presents a major challenge in this dataset, where non-fraudulent transactions far outnumber fraudulent ones.

# This project has 3 parts: 

- Exploratory Data Analysis: Univariate, Bivariate, and Multivariate. 

- Data Cleaning + Wrangling

- Modeling

# Import Columns from Dataset

- Step: A unit of time that represents hours in the dataset. 
Think of this as the timestamp of the transaction (e.g. hour 1, hour 2, … hour 534, …) 
- Type: The type of transaction 

- Amount: The amount of money transferred 

- NameOrig: The origin account name 

- OldBalanceOrg: The origin accounts balance before the transaction 

- NewBalanceOrg: The origin accounts balance after the transaction 

- NameDest: The destination account name 

-  OldbalanceDest: The destination accounts balance before the transaction 

- NewbalanceDest: The destination accounts balance after the transaction 

- IsFlaggedFraud: A “naive” model that simply flags a transaction as fraudulent if it is greater than 200,000 (note that this currency is not USD) 

- IsFraud: Was this simulated transaction actually fraudulent? In this case, we consider “fraud” to be a malicious transaction that aimed to transfer funds out of a victim’s bank account before the account owner could secure their information.



