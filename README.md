# Amazon_Vine_Analysis

## Overview

The aim of this analysis is to dive deeper into Amazon reviews written by members of the paid Amazon Vine program to determine if there is a bias toward favorable reviews from Vine members specifically. This analysis focused on video games, used PySpark to perform the ETL process of extraction and transformation, connected to AWS RDS, and utilized pgAdmin. 

Data Source
https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz

## Results 

Total # of Vine Reviews: 49

![total_vine_reviews](https://github.com/saraglenn/Amazon_Vine_Analysis/assets/119461431/3155839e-9546-443f-99b4-21b6618d3070)

Total # of non-Vine Reviews: 40,471

![total_nonvine_reviews](https://github.com/saraglenn/Amazon_Vine_Analysis/assets/119461431/f10bdf11-90e5-45dc-8a44-5fb5b048d160)


Total # of Vine 5- Star Reviews: 48

![5_star_vine_reviews](https://github.com/saraglenn/Amazon_Vine_Analysis/assets/119461431/a2636587-65a1-46d9-b3d1-a3158bf09324)


Total # of non-Vine 5- Star Reviews: 15,663

![5_star_nonvine_reviews](https://github.com/saraglenn/Amazon_Vine_Analysis/assets/119461431/9798c779-de3e-4779-a9f7-4bb403767a7f)


Percentage of Vine Reviews = 5- Stars: 51.06%

![percent_vine_5_star](https://github.com/saraglenn/Amazon_Vine_Analysis/assets/119461431/1c4f569b-7d05-47a8-8b67-b0dd71735310)


Percentage of non-Vine Reviews = 5- Stars: 38.7%

![percent_nonvine_5_star](https://github.com/saraglenn/Amazon_Vine_Analysis/assets/119461431/75474b41-4ef6-4c44-9491-b89204f6df4b)




