P2P Lending Loan Book Analysis
===========


What is the problem you want to solve?
-----------------
The plan is to analyse a P2P lending platform's loan book in order to predict (estimate expected return) of a loan portfolio at any point in its lifetime.


Who is your client and why do they care about this problem? In other words, what will your client DO or DECIDE based on your analysis that they wouldn’t have otherwise?
-----------------
The client is either a sophisticated individual investor or an instutional investor. The client may hold a loan portfolio with the P2P lending platform or is planning to. Based on the analysis the client may decide how to build the portfolio or modify it (by selling part of it or buying more loans) in order to maximize the profit.

What data are you going to use for this? How will you acquire this data?
-----------------
Loan book data and historic payments file provided by Bondora is going to be used for the project. The files are publicly accessible on Bondora website.

In brief, outline your approach to solving this problem (knowing that this might change later).
-----------------
The approach is to calculate the expected return of a loan (using combination of loan features and historical repayment of similar loans) at the start of the loan.
Additionally, over time the loan's expected return might change and the aim is to generate a curve that estimates this behaviour.
This will allow for calculating the expected return of the whole portfolio.

What are your deliverables? Typically, this would include code, along with a paper and/or a slide deck.
-----------------
The deliverables are:
- a paper that describes the approach and results
- a jupyter notebook that allows for upload of a loan portfolio file and expected return calculation
