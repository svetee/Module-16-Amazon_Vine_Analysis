# Amazon_Vine_Analysis

## Overview 
This project was utilizing Amazons RDS and uploading that data into PostgreSQL to query data either in SQL or in Jupyter Notebooks: Google Collaboratory. With this specific dataset we are going to determine if there was a bias with Amazon review on Sports Items for the Vine Program. The Vine Program for Amazon is a invitation only based program in which Amazon wants to get the most trusted reviewers on Amazon to post opinions about new and pre-release items to help their fellow customers make informed purchase decisions. 

## Results
![Screen Shot 2020-11-01 at 1 02 13 PM](https://user-images.githubusercontent.com/67808057/97816793-8c304d00-1c4c-11eb-8a85-050d253183eb.png)

### How many Vine reviews and non-Vine reviews were there?
- Vine: 334  
- Not-Vine: 61614

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- Vine: 139
- Not-Vine: 32665

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- Vine: 41.62%
- Not-Vine: 53.02%

## Summary 
In conclusion, for the Sports Items in the Vine Program there the test is inconclusive since our number of total reviews for Vine is significantly lower than Not-Vine Reviews plays a major role in this analysis. But going on what this data is telling me I would say that there is negative bias since it is about 12 percentage points lower than non-Vine revewis. We would need to have way equal or signtly less Vine reviews to non-vine reviews to gather a more insightful answer to this problem. We could use ANOVA testing but of course would still need a larger sample to use this statistical test. Another way is that we could randomly select reviews on both groups then determine their percentages and see if there is a positive bias in the Vine Program reviews.
