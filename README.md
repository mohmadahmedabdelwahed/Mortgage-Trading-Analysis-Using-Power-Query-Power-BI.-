# Mortgage-Trading-Analysis-Using-Power-Query-Power-BI.-
A full end-to-end analysis simulating the role of a junior mortgage trader at a U.S. non-bank lender. The project includes data cleaning, loan quality assessment, bid price evaluation, UMBS benchmarking, trade premium calculation, profit margin analysis, and final trade execution.

## Summary: 

This project simulates the role of a junior mortgage trader at Sooper Mortgage, a fictional U.S. non-bank lender. The objective is to execute a mortgage trade in the capital markets by analysing mortgage-level data, investor bid prices, and benchmark UMBS prices to maximize Sooper Mortgage’s profit. 

Using Power Query for data cleaning and modelling, and Power BI for analytics and visualization, the project evaluates loan quality, bid competitiveness, projected principal balances, trade premiums, gross profit, and achievement of the firm’s target profit margin. 
The final analysis identifies the optimal counterparty, the profitability of each loan, and key insights about borrower characteristics affecting pricing. 

## Business Problem: 

Sooper Mortgage sells mortgage loans to investors in the secondary market. To maximize profit, the firm must: 
1. Identify which loans are ready to trade. 
2. Calculate accurate scheduled principal balances at settlement date between 21/9/2021 &13/10/2021. 
3. Compare Whole loan investor bids against UMBS benchmark prices. 
4. Calculate trade premiums and expected gross profit. 
5. Determine whether trades meet or exceed the firm’s target profit margin. 

## The challenge is ensuring the data is clean, accurate, and merged properly to support reliable trade execution. 

## Results:

1. 26.15% of loans outperformed UMBS benchmark. 
2. Optimal buyer: Storgan_Manley which has highest amount of revenue (trade amount) & profit (trade premium). 
3. The company achieved profit margin 7%, exceeding 5% target. 
4. Total trade premium (profit) on profitable loans: $8.3M+ 
5. FICO score is a strong price driver → higher FICO → higher price.

![Image Alt](


## Business Recommendations:

1. The company must Sell to Storgan_Manley as the primary counterparty based on pricing strength. 
2. The company must avoid selling to Smells_Largo due to minimal contribution to premium trade (less than 2%). 
3. The company can enhance pricing strategy: introduce FICO-based pricing tiers and reducing the fees for borrowers with higher FICO scores. 
4. The company must improve internal data readiness, so more loans qualify as “ready to trade.” 

## Skills Demonstrated: 

Power Query (Data Cleaning, M Language, Merging, Modelling) 
Power BI (DAX Measures, Visualizations, Data Modelling) 
Financial concepts: 
Loan amortization 
LTV, DTI, credit risk 
Mortgage trading / secondary markets 
Trade premium & profit margin calculations 
Benchmarking analysis (UMBS vs bids) 
Analytical storytelling & trade decision justification 
