# Amazon_Vine_Analysis

## Analysis Overview
The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies participating in this program pay a small fee to Amazon and in turn, provide products to Amazon Vine members, who are required to publish a review.

This analysis reviews a dataset of Amazon pet products reviews to determine if there is any bias toward favorable reviews from Amazon Vine members within the dataset.

## Results
The results below are for the Amazon pet products dataset, located within AWS here - https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Pet_Products_v1_00.tsv.gz

### Paid Program Reviews
- Total number of Vine reviews: 170
- 5-star Vine reviews: 65
- Percentage of Vine reviews that were 5-star: 38.24%

### Unpaid Program Reviews
- Total number of non-Vine reviews: 37,840
- 5-star non-Vine reviews: 20,612
- Percentage of non-Vine reviews that were 5-star: 54.47%

## Summary
Based on analysis above of Amazon pet product reviews, there does not appear to be a positivity bias for reviews in the Vine program, as the percentage of 5-star reviews is approximately 16% greater for the non-Vine reviews.

To further support this determination about positivity bias, an analysis of the the mean star ratings for verified purchases with Vine- and non-Vine reviews can be conducted.
