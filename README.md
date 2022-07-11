# Amazon Vine Analysis

## Purpose
The purpose of this analysis is to determine if there is bias in 5-star reviews of Amazon Pet Products that are part of the Vine Paid Program. 

## Results

For this analysis I divided the data into two DataFrames, one for reviews that were part of the Vine Paid program, and one for all non-Vine reviews:

Vine Paid Reviews

![Vine_Paid_Reviews](https://github.com/nikkiheaston/Amazon_Vine_Analysis/blob/main/Vine_Paid_Reviews.PNG)

Vine Unpaid Reviews

![Vine_Unpaid_Reviews](https://github.com/nikkiheaston/Amazon_Vine_Analysis/blob/main/Vine_Unpaid_Reviews.PNG)


- This analysis revealed that there were 170 Vine reviews and 37,840 non-Vine reviews.
- The number of Vine reviews that contained 5 stars was 65. And the number of non-Vine reviews that contained 5 stars was 20,612.
- The percentage of Vine reviews that were 5 stars was approximately 38% and the number of non-vine reviews that were 5 stars was approximately 55%.

## Summary
From this analysis I have concluded that there is not positivity bias towards 5-star reviews in the Vine Paid Program. The percentage of 5-star unpaid reviews is much higher than for the paid program. To further research this issue I would perform an additional analysis by filtering the verified purchases data to ensure the reviews are for verified purchases only and not fake, scam, or unverified purchases that may skew the data.
