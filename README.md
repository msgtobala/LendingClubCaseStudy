# Lending club case study
> Minimize the risk of losing money while rending to customers using EDA


## Table of Contents
- [Lending club case study](#lending-club-case-study)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
    - [Problem Statement](#problem-statement)
    - [Objective](#objective)
  - [Conclusions](#conclusions)
  - [Technologies Used](#technologies-used)
  - [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Problem Statement
When a person applies for a loan, there are two types of decisions that could be taken by the company: 
1. Loan accepted: If the company approves the loan, there are 3 possible scenarios described below,
     a. Fully paid: Applicant has fully paid the loan (the principal and the interest rate) 
     b. Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'. 
     c. Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan
2. Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

### Objective
- Identify variables that provide strong indicators of potential loan default thus helping Lending club to decide approval/rejection of loan. 
- Identification of such applicants using EDA is the aim of this case study
- Perform EDA operations like.
- Data Cleaning
- Univariate Analysis
- Segmented Analysis
- Bivariate Analysis
- Derived Metrics

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Income range 40-50k has high chances of charged off.
- Rent and Mortgage applicants are high percentages of loan defaulter
- Small business have high chances of loan defaults
- HI States is holding highest number of loan defaults
- Those loan has been issued in month of March is having low number of loan defaults
- 2009 is having lowest loan defaults and 2007 is having highest loan defaults
- The Loan applicants with loan Grade F is having highest Loan Defaults.
- Those loan has been issued in Feb, Aug and Nov is having high number of loan defaults


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- numpy
- pandas
- seaborn
- Matplotlib

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@msgtobala] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->