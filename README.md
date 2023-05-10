# Lending Club case study
```
Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). 
Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs 
away with the money owed.

Main objective is to identify these risky loan applicants, then such loans can be reduced thereby 
cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of 
this case study.

Performing analysis on the driving factors (or driver variables) behind loan default, i.e. the variables
which are strong indicators of default.  The company can utilise this knowledge for its portfolio and 
risk assessment. 

```

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
 - Analysis the dataset for Lending Club
- What is the background of your project?
 - consumer finance company which specialises in lending various types of loans to urban customers. we nned to find the factors those are defaults.
- What is the business probem that your project is trying to solve?
 - lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed
- What is the dataset that is being used?
 - loan data sets

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
###  univariate analysis with respect to the charged off loans. There is a more probability of defaulting when : 

- Applicants having house_ownership as 'RENT'
- Applicants who use the loan to clear other debts
- Applicants who receive interest at the rate of 13-17%
- Applicants who have an income of range 31201 - 58402
- Applicants with employement length of 10
- When funded amount by investor is between 5000-10000
- Loan amount is between 5429 - 10357
- Dti is between 12-18
- When monthly installments are between 145-274
- Term of 36 months
- When the loan status is Not verified
- When the purpose is 'debt_consolidation'
- Grade is 'B'
- And a total grade of 'B5' level.

###  Bivariate/multivariate analysis with respect to the charged off loans. There is a more probability of defaulting when : 

- Applicants taking loan for 'home improvement' and have income of 60k -70k
- Applicants whose home ownership is 'MORTGAGE and have income of 60-70k
- Applicants who receive interest at the rate of 21-24% and have an income of 70k-80k
- Applicants who have taken a loan in the range 30k - 35k and are charged interest rate of 15-17.5 %
- Applicants who have taken a loan for small business and the loan amount is greater than 14k
- Applicants whose home ownership is 'MORTGAGE and have loan of 14-16k
- When grade is F and loan amount is between 15k-20k
- When employment length is 10yrs and loan amount is 12k-14k 
- When the loan is verified and loan amount is above 16k
- For grade G and interest rate above 20%

### The above analysis is correlation between some variables. There is a more probability of defaulting when : 

- Applicants are in more dark annual income colors for heat map plt first
- Applicants were applied the most loan in 2009 and 2011 because 2009 and 2011 are having highest correlation value for heat map second.
- Applicant were applied the most loan for employeed 8 and 10 years are having highest correlation value for heat map third.
- Applicant were applied the most interest rate in 2009 to 2011 are having highest correlation value for heat map fourth

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas library
- numpy library
- matplotlib chart libary
- seaborn chart libary

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

### Contributors
- Indraneel Pradhan
- Truong Nguyen Manh


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->