# Project Description
To build a model for predicting money borrowers who have a profile of having a high probability of paying back.

## Background Information

Exploring publicly available data from LendingClub.com. Lending Club connects people who need money (borrowers) with people who have money (investors).I am trying to create a model that will help predict people who have a profile of having a high probability of paying back.

## Data Description

- __credit.policy:__ 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
- __purpose:__ The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").
- __int.rate:__ The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.
- __installment:__ The monthly installments owed by the borrower if the loan is funded.
- __log.annual.inc:__ The natural log of the self-reported annual income of the borrower.
- __dti:__ The debt-to-income ratio of the borrower (amount of debt divided by annual income).
- __fico:__ The FICO credit score of the borrower.
- __days.with.cr.line:__ The number of days the borrower has had a credit line.
- __revol.bal:__ The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).
- __revol.util:__ The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).
- __inq.last.6mths:__ The borrower's number of inquiries by creditors in the last 6 months.
- __delinq.2yrs:__ The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
- __pub.rec:__ The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).

## Techniques used

* Dummification to handle Categorical variables.

## Models 
* Decision Tree
* Random Forests
