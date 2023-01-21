# Mini-project IV

### [Assignment](assignment.md)

## Project/Goals
Use provided data to predict who is more likely to get loan approved, considering all the provided parameters and columns in the data set.
There 3 main factors that make you a good candidate for a Loan:
  Credit history and score
  Income
  Debt-to-income ration

## Hypothesis
  Looking at the data provided, we have the following that matches the key requirements for the loan approval:
  Applicant Income
  Credit History
  And some information about those who apply: gender, education, loan_status

## EDA 
1. Key findings:
475 applicants have credit history. That gives these applicants the first advantage
Applicant Income is higher than the Co-applicant Income. Some of the co-applicants did not hav have income, so as requested in the task, I’ve changed that value to mean value.

2. Loan Status:
68.7% Yes
31.3 % No

3. Box plot visualization for the Applicant income before and after handling the outliers more evenly distributed

4. Relation between Applicant Income and Loan Amount: Loan amount is higher for those within $10K income amount

4. The loan amount requested by males is higher than by females. Married people requested loan amount is generally higher than the unmarried.


## Process

1. Loaded the data and reviewed 
2. Handled possible NaN Values, replaced them with mean values after
3. Looked at the box plots and Histograms for ApplicantIncome, Loan_Amount and categorical data like: gender, marital status, education etc
4. Handled the outliers w=to see the difference: more evenly distributed after handling the outliers
5. Looked at the CombinedIncome by creating a new colum (adding 2 incomes together)
6. Reviewed relation Between Applicant Income vs Loan Amount 
7. Created heatmap to look at the features
8. Built Logistic regression to predict the possible loan approval

## Results/Demo
Credit_History like it was predicted at the beginning has the most influence on the loan approval 
The other features have minimal or no influence.

Property_Area, Loan_Amount, Co-applicant Income, dependents and marital status have some influence as well but Credit History remains the main feature in decision making

## Challanges 
1. Outliers
2. Not available credit-score

## Future Goals
Do more EDA and see any other possible interesting discoverings, maybe work on a real time project.
