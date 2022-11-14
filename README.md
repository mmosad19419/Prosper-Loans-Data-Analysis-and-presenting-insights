## Banking Loans Analysis
### by Mohamed Mosad

### Dataset
Exploratory data analysis for loan status and what factors affect the loan status using [Loan data From Prosper](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv), This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.See this [Data Dictionery](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) to understand the dataset's variables.

Through this notebook i will apply Exploratory analysis,and Explanatory analysis and use the findings and present them. 


## Summary of Findings

#### Quantitative features investigated and analized
- `EstimatedEffectiveYield`	Effective yield is equal to the borrower interest rate (i) minus the servicing fee rate, (ii) minus estimated uncollected interest on charge-offs, (iii) plus estimated collected late fees.  Applicable for loans originated after July 2009.

- `ProsperScore`	A custom risk score built using historical Prosper data. The score ranges from 1-10, with 10 being the - best, or lowest risk score Applicable for loans originated after July 2009.

- `LoanOriginalAmount`	The origination amount of the loan.

#### Qualitative features investigated and analized
- `Term`	The length of the loan expressed in months.

- `LoanStatus`	The current status of the loan: Cancelled,  Chargedoff, Completed, Current, Defaulted, FinalPaymentInProgress,  - PastDue The PastDue status will be accompanied by a delinquency bucket.

- `ListingCategory`	
The category of the listing that the borrower selected when posting their listing:
1 - Debt Consolidation
2 - Home Improvement
3 - Business
4 - Personal Loan
5 - Student Use
6 - Auto
7- Other
8 - Baby&Adoption
9 - RV
10 - Cosmetic Procedure
11 - Engagement Ring
12 - Green Loans
13 - Household Expenses
14 - Large Purchases
15 - Medical/Dental
16 - RV
17 - Taxes
19 - Vacation
20 - Wedding Loans

- `EmploymentStatus`	The employment status of the borrower at the time they posted the listing.

- `IsBorrowerHomeowner`	A Borrower will be classified as a homowner if they have a mortgage on their credit profile or provide documentation confirming they are a homeowner.


### Through the notebook
- Data loading
- Wrangling and cleaning
- Investigation of each variable and its distribution
- Relation analysis between each categorical variable and the three Quantitative variable
- Multi-variate analysis 


## Key Insights for Presentation
> What is charactristic of each loan status in each quantitative metric [EstimatedEffectiveYield, ProsperScore, LoanOriginalAmount]?

> What is the categories of borrower who has access to high loan original amount?

> What is the preferred loan term in each listing category?

> What is charactristic of each loan term in each quantitative metric [EstimatedEffectiveYield, ProsperScore, LoanOriginalAmount]?

> What factors affect a defaulted loans loan’s outcome status?

> What charactristic of defaulted loans loan’s outcome status in term of each quantitative metric [EstimatedEffectiveYield, ProsperScore, LoanOriginalAmount]?