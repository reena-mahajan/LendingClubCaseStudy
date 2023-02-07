# Project Name
Lending Club Case Study

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information

We are working for a consumer finance company which specialises in lending various types of loans to urban customers (Lending Club). When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.
Two types of risks are associated with the bank's decision:
- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

- Business Problem
    The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. That is company wants to undersatand the driving factors behind the loan defaults

- Data Set
    Provided data contains the information about past loan applicants and whether they 'defaulted' or not.

- Problem Solving Methodology
    * Data Understanding-
        > Understanding data points using data dictionary, understanding the meanning of all the columns and their domain specific uses.
    * Data Cleaning-
        > Removing all null valued columns, single uniques columns, unnecessary columns, data type conversion, removing outliers, deriving new variables.
    * Univariate Analysis-
        > Analysing each columns and plotting the distribution of each to get more information.
    * Segmented Univariate Analysis-
        > To get more insights of single data variables using segments.
    * Bivariate Analysis-
        > Analysing two variables and relationship between them by plotting diffrent graphs
    * Recommendations-
        > Provided the list of recommendations to the investors so that they can avoid giving loans to high risk customers

## Technologies Used
- Python - version 3.9.13
- Libraries Used - Pandas , Numpy , Matplotlib , Seaborn, Plotly

## Conclusions
    - Verification System : From the analysis it came out that even if the verification is done than also there are defaulters and are nearly same as those of loans that are not verified, company can check its verification process
    - State Verification : Most of the defaulters are from 'CA'
    - Loan Purpose check : Loan taken for clearing other debts and for small business had high number of defaulters than in other categories
    - Home Ownership : Customers who were on Rent or had mortgage and borrowed loan between 14K to 16K tend to default more than other categories
    - Term : Customers who had Loan term as 36 months are tend to default more than with loan term of 60 months
    - Loan Amount and Interest Rate : Customers who had taken loan amount between 30K to 35K with higher interest rate i.e.17.5% tend to default more than others having low interest rate.
    -  Grade : Loan grade B had higher number of defaulters and loan grade F with loan amount between 15000-20000 tend to default more than others.
    - Employment Length : Customers who had employment length 10 years or above tend to default more than others.
    - Customer Annual Income : Customers who had annual income between 2 K to 32 K tend to default more than others.
    - Dept to Income Ratio : Customers who had their dept to income ratio lies between 12-18 tend to default more than others.

## Acknowledgements
    - https://www.lendingclub.com/
    - Contributors
        * [Reena Mahajan]
        * [Nirali Bhansali]