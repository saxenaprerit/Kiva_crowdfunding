# Kiva_crowdfunding
Analysis of Kiva Crowdfunding data

Objective:
The objective is to do an exploratory analysis on the Kiva dataset available online on Kaggle.

Data:
The source of the data is https://www.kaggle.com/kiva/data-science-for-good-kiva-crowdfunding
The dataset contains 4 files:
•	Kiva_loans.csv
•	Kiva_mpi_region.csv
•	Loan_theme_ids.csv
•	Loan_themes_by_region.csv

Approach:
Exploratory data analysis has been done on the datasets to identify major sectors where loan is given, major lenders etc.
Further, random forest has been run on the dataset to identify major factors for repayment interval.

Instructions:
Please have the following python libraries installed before running the jupyter notebook
•	Numpy
•	Pandas
•	Matplotlib
•	Seaborn
•	Folium
•	Squarify
•	Sklearn

Set the working directory to the folder where the input files are located.

Results:
Following sectors take the highest loan amount:
•	Farming
•	General Store
•	Clothing Sales
•	Agriculture
•	Retail

As a result of the analysis, I have concluded that the factors determining repayment interval type are the following in the decreasing order of their importance:
•	Term in months
•	Loan Amount
•	Lender count
•	Disbursed time
