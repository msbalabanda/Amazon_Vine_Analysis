# Amazon_Vine_Analysis

## Overview of the analysis
This project is based on amazon reviews for video games.use We use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then we use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. The goal is to try to determine if there is favorable review bias from the Vine members in the data set.

## Results
1) How many Vine reviews and non-Vine reviews were there?
There were a total of of 4,291 vine reviews in our dataset, and 40,471 non-vine reviews in the complete dataset.

2) How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
There are 15,711 5-star reviews and 15,663 non-vine 5-star reviews

3) What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
38.2% of vine reviews were five stars and 38.9% of non-vine reviews were 5 stars

## Summary
38.2% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 38.9%. Therefore there does not appear to be any sort of positivity bias because the percentages shown above are very similar.An additional analysis to perform on this data set would be to establish the measures of central tendency (mean, median, mode) on the star_rating variable. This would be useful to see if the data is skewed either way. We could then see what the average star ratings were for Vine and non-vine reviewers. 
