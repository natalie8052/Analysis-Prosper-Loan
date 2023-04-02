# Prosper Loan Data Exploration
Analysis and visualization of what purpose borrowers use loan
## by Natalie Nguyen


## Dataset

The dataset comprises 113,937 loans with 81 variables for each loan, including borrower income, loan amount, borrower rate (interest rate), current loan status, and several other variables. The dataset can be found [here](https://www.google.com/url?q=https://www.google.com/url?q%3Dhttps://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv%26amp;sa%3DD%26amp;ust%3D1581581520570000&sa=D&source=editors&ust=1680228808838503&usg=AOvVaw2ZhuLaV97qIFehzFzaZJHE) and feature documentation available [here](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&source=editors&ust=1680228808839437&usg=AOvVaw2NcoT5Kff74ljns9W-il6u)

## Summary of Findings

In the exploration, I found several significant findings related to borrower motivations and factors affecting their decision-making process when selecting a loan. The correlation relatiomship of APR, Rate, Loan Original Amount, and Monthly Loan Payment are strongly positive. Moreover, I found that CreditScoreMean has a strong negative correlation with Rate and APR, meaning that higher credit scores correspond to lower interest rates and annual percentage rates. Furthermore, the result shows that there is a moderate positive correlation between Term that borrowers tend to opt for longer loan terms when borrowing higher amounts.

I also found that credit score is a significant factor in determining loan terms, with higher scores leading to lower interest rates and higher loan amounts. Additionally, higher loan amounts and payments are associated with lower APR and interest rates. 

About the borrowers profile, it is found that borrowers with higher IncomeRanges were able to obtain larger Loan Original Amounts at lower BorrowerRates, while still being able to manage their DebtToIncomeRatios. It is also observed that borrowers with loan purposes such as debt consolidation, home improvement, household expense, medical, or dental generally have a lower debt-to-income ratio, with values lower than 0.5. Conversely, borrowers with loan purpose of baby and adoption tend to have higher DTI.


## Key Insights for Presentation

For my presentation, I will focus on the distribution of ListingCategory and its trends in other related features such as DebtToIncomeRatio, employment status, and income range. Then, I will discuss the correlations of BorrowerRate, BorrowerAPR, LoanOriginalAmount, and MonthlyLoanPayment with borrower purpose. I'm only use some plots for easy understanding about the trends. 
