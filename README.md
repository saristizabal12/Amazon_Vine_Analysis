# Amazon_Vine_Analysis

You'll transform the DataFrame into four separate DataFrames that match the table schema in pgAdmin. Then, you'll upload the transformed data into the appropriate tables and run queries in pgAdmin to confirm that the data has been uploaded.

After we determined if there is any bias towards reviews that were written as part of the Vine program. For this analysis, we'll determine if having a paid Vine review makes a difference in the percentage of 5-star reviews.

### Deliverable 1: Perform ETL on Amazon Product Reviews

#### Image below shows that we are reading the Review dataset as a DataFrame

![image](https://user-images.githubusercontent.com/100005305/195481765-ed73282c-3bf9-4b90-be7c-8f75c9700dde.png)

#### Image below shows that we are creating the customers table DataFrame

![image](https://user-images.githubusercontent.com/100005305/195482002-55d01111-1bf3-42de-b0eb-3166a519f781.png)

#### Image below shows creating the products table DataFrame and drop duplicates

![image](https://user-images.githubusercontent.com/100005305/195482063-9bfdca77-8e34-4db0-ba91-1dbbe81ca3ed.png)

#### Image below shows creating the products table DataFrame and drop duplicates.

![image](https://user-images.githubusercontent.com/100005305/195482293-bd26190f-1b81-4c0f-99ad-628b7e2d2957.png)

#### Image below shows converting the'review date' column to a date datatype with to a review date

![image](https://user-images.githubusercontent.com/100005305/195482263-8a538865-4b23-4785-8318-b326ab4aac5b.png)

#### Image below shows creating the vine table DataFrame

![image](https://user-images.githubusercontent.com/100005305/195482529-12cabe67-df17-40b0-8320-2467e214a1fe.png)

Image below shows the review_id_table that we imported to SQL

![image](https://user-images.githubusercontent.com/100005305/195481905-0cf81b20-7300-4792-b1b1-3a35e3b870e5.png)

### Deliverable 2: Determine Bias of Vine Reviews

This image below shows that we removed null values from our DataFrame
![image](https://user-images.githubusercontent.com/100005305/195482999-252d9306-5d7b-4e2b-acec-79366c97ee88.png)

We created the vine table DataFrame with no null values

![image](https://user-images.githubusercontent.com/100005305/195483138-ea1a4be3-1d77-4f5a-a0d0-ff2d59f5c8e8.png)

Determine the total number of reviews, the number of 5-star reviews, and the percentage of 5-star reviews

![image](https://user-images.githubusercontent.com/100005305/195483189-8c864469-0ce9-4b85-885a-9f65bcfcd958.png)


### Deliverable 3: A Written Report on the Analysis (README.md)

How many Vine reviews and non-Vine reviews were there?
How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
