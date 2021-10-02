# Bank-Loan-Approval-Prediction
Deep neural network model predicts the approval of a personal loan based on features like age, experience, income, locations, family, education, mortgage, credit card etc.

### Prerequisites

[Python 3](https://www.python.org/downloads/)

Tensorflow<br/>
`pip install tensorflow`

#### About the Dataset (From [Kaggle](https://www.kaggle.com/itsmesunil/bank-loan-modelling))

The data set includes 5000 observations with fourteen variables divided into four different measurement categories. The binary category has five variables, including the target variable personal loan, also securities account, CD account, online banking and credit card. The interval category contains five variables: age, experience, income, CC avg and mortgage. The ordinal category includes the variables family and education. The last category is nominal with ID and Zip code.

Features:
- *ID*: Customer ID
- *Age*: Customer's age in years
- *Experience*: Number of years of professional experience
- *Income*: Annual income of customer ($)
- *ZIPCode*: Home address ZIP code
- *Family*: Family size of the customer
- *CCAvg*: Average spending on credit cards per month ($)
- *Education*: Education level (1: Undergrad; 2: Graduate; 3: Advanced/Professional)
- *Mortgage*: Value of house mortgage ($)
- *Personal Loan*: Did this customer accept the personal loan offered in the last campaign or not?
- *Securities Account*: Does the customer have a securities account with the bank?
- *CD Account*: Does the customer have a certificate of deposit (CD) account with the bank?
- *Online*: Does the customer use internet banking facilities?
- *CreditCard*: Does the customer use a credit card issued by UniversalBank?
