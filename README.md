# Bikes Sales Dashbboard


A bike selling company wanted to find what all are the key factors that influence the bike sales and the company wanted to tailor 
their marketing strategies based on that.

![Bike Sales Dashboard](https://github.com/moaazelsokary/Bike-Sales-Analysis/blob/main/Screenshot_1.png)


## About Data:
Bike sales data which is used for analysis is collected from Kaggle.

## Attributes
* Id : Unique ID to identify each customer
* Marital status : Whether Married or Single
* Gender : Whether Male or Female
* Income : Income of the customer in US dollars
* Children : No. of children in the Family
* Education : Education of customer
* Occupation : Current occupation of the customer
* Homeowner : Does the customer own a home
* Cars : No. of cars owned by the customer
* Commute distance : Commute Distance of each customer
* Region : Region of the customer
* Age : Age of the customer
* Purchased bike : Whether purchased or not





As a Data Analyst, to identify the factors that can influence bike sales following steps are performed

## Tool Used
Microsoft Excel

## Data Cleaning and Data Manipulation
* Removed rows which had missing values 
* Checked datatype of each column
* Removed duplicate values from the data
* Replaced values in the columns like Gender and Marital Status for easy understanding
* Added a column named 'Age Bracket', by using Nested IF condition

## Insights

2. Commute Distance Analysis:
    * Customers who had to commute 0-5 miles were more likely to purchase bikes.
    * There was a decline in the purchase of bikes for customers over 10 miles of commute distance.
3. Age and Gender Analysis:
    * Middle-aged customers (31-55) purchased more bikes compared to adolescents and older customers.
    * Males were found to have higher income than females, and customers with higher salaries were more likely to purchase bikes.
    * Female customers in clerical and skilled manual occupations were more likely to purchase bikes than male customers.
4. Occupation Analysis:
    * Customers with an occupation as manual workers and who were older (56 and above) did not purchase bikes.

## Recommendations

#### Target Middle-aged Customers:
* Since middle-aged customers purchased most bikes, the company could focus their marketing campaigns on middle age, emphasizing the benefits of owning a bike for fitness and commuting
#### Offer Discounts for Short Commute Distances:
* As customers who had to commute 0-5 miles were more likely to purchase bikes, the company could offer discounts on bikes for customers who have a short commute distance. This could attract more customers who are looking for a cost-effective mode of transportation.
#### Focus on Female Customers:
* Since female customers in clerical and skilled manual occupations were more likely to purchase bikes than male customers, the company could create marketing campaigns that target female customers. This could include highlighting bikes that are designed specifically for women, promoting the health and wellness benefits of cycling, and showcasing female cyclists in marketing materials.



## Future Scope
This same data can be analyzed and visualized by more complex Business Intelligence Tools like Quicksight, PowerBI etc.

