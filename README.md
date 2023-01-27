# Amazon_Vine_Analysis
## Overview of the analysis: 
For this project we are analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. We used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then we determine if there is any bias toward favorable reviews from Vine members in the dataset. 

# Results:

## Summarizing the results to answer the following questions.

### 1. How many Vine reviews and non-Vine reviews were there?

![Screenshot (237)](https://user-images.githubusercontent.com/112904905/215130191-8d39fa73-2f6d-4754-a100-6cc21c3c0d7f.png)

![Screenshot (238)](https://user-images.githubusercontent.com/112904905/215130675-f4103873-a444-4489-a408-03a54c68847b.png)

### 2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

![Screenshot (239)](https://user-images.githubusercontent.com/112904905/215131013-ccd55a58-c35a-4b5d-a964-bce471a66540.png)

### 3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

![Screenshot (240)](https://user-images.githubusercontent.com/112904905/215132084-aa6fa706-687e-46a6-9f38-7ca990825e66.png)
 
Percentage of vine reviews is 34.12322274881517
Percentage of not vine review is 48.32752725630605

# Summary: 

As the results suggests there is a high percentage of vine reviews in total. Though total number of 5 star vine review is 432 as compared to not vine 5 star review which is 29965 for our toys dataset. This does not necessarily suggest a positve bias as the number is not high compared to non vine review. 
Some other analysis that may help to get a better picture of the vine program may be the age/gender bias or how often a vine member gives 5 star reviews for products given to them.
