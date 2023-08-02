# Telecommunications-Customer-Churn-Project

![](https://github.com/samuelejedegba/Telecommunications-Customer-Churn-Project/blob/main/Telecommunicatons%201.jpg)

## Introduction
This is a churn data for a fictional Telecommunications company that provides phone and internet services to 7,043 customers in California and includes details about customer demographics, location, services and current status.

## Recommended Analysis
1.	How many customers joined the company during the last quarter? How many customers joined?
2.	What is the customer profile for a customer that churned, joined, and stayed? Are they different?
3.	What seem to be the key drivers of customer churn?
4.	Is the company losing high-value customers? If so, how can they retain them?

## Skills/Concepts Demonstrated
1. SQL
2. Power BI

## Cleaning and Analysis
The Cleaning and Analysis was done with SQL. The indept Analysis will be shown here, but the SQL queries can be found [here](https://github.com/samuelejedegba/Telecommunications-SQL-Project/blob/main/Communication%20query.sql).
The above link shows the codes and detailed explanation of my thinking behind each query and what exactly I was achieve. It also answers the above questions and gives my recommendations, however, I still highlight my recommendations in this post.

## Results
1. How many Customers Joined the company in the last quarter?

The above question was answered in [here](https://github.com/samuelejedegba/Telecommunications-SQL-Project/blob/main/Communication%20query.sql) in my SQL analysis. It was also highlighted in the Power BI analysis below using the filter function to highlight the customers that joined in the service in the last 3 months.
1051 Customers joined in the last 3 months, which is the last quarter of the year.

2. What is the customer profile for a customer that churned, joined, and stayed? Are they different?

This was also analysed in my [SQL analysis](https://github.com/samuelejedegba/Telecommunications-SQL-Project/blob/main/Communication%20query.sql) where I created 3 smaller tables from the main table using the 'Stayed', 'Joined', and 'Churned' customer profiles. I analysed the average age, marriage status, Number of referrals, internet type, etc. Some useful insights were gotten from this analysis which drew some recommendations that will be highlighted below.

3. What seem to be the key drivers of customer churn?

This was also analysed in my [SQL analysis](https://github.com/samuelejedegba/Telecommunications-SQL-Project/blob/main/Communication%20query.sql) and drew some recommendations for the telecommunications company. Customer churn was mostly driven by City, Competition, Attitude of support person, Internet Type, Offers Given and Length of Contract.

4. Is the company losing high-value customers? If so, how can they retain them?

The simple answer is Yes. I examined the number of customers that spend above the average monthly bill for all the customers and out of 1869 churned customers, 1343 spend the average monthly charge or above. These are some high value customers.

## Power BI Visual
I created a simple power BI visualisation to show these analysis better highligthing the important categories and tell the story of why the churn rate in this company is so high.

![](https://github.com/samuelejedegba/Telecommunications-Customer-Churn-Project/blob/main/Telecommunications%20BI.PNG)

## Conclusions and Recommendations

1. In my analysis, I discovered 624 customers with at least one referral left the service while 1245 of customers with no referrals left the service. The huge discrepancy in numbers shows that people who refer others to the service are more likely to stay than those who don't. 

Recommendation: A plan to reward those who refer others to the service must be put in place as it does not just only bring others to the service, it also likely ensures customer loyalty.

2. People using Fiber Optic are the highest churned customers (1236). However, DSL users tend to be more loyal (1230 stayed while only 307 left).

Recommendation: Fibre Optic are usually more reliable and faster than DSL. People that use Fiber Optic leaving might be a service delivery problem. The service of the fibre optic internet should be looked into and improved upon to reduce churn rate.

3. People with a month to month contract are obviously leaving the most (the number is 1655). People with one and two year contracts are staying with the service more.

Recommendation: There should be a reward system for customers with more than a month contract. A discount for all services to ensure new users take up longer than a month contract. The 'Joined' table proves that new customers are not taking longer contracts. out of 454 customers that joined, only 24 took the one year contract and 22 the two year contract. A whooping 408 opted for the Month-to-Month contract. More has to be done to ensure people go for longer contracts in order to keep them.

4. Examining the Cities of the customers that left the service, the followig discoveries were made:

   a. Los Angeles has the highest number of customers that stayed with 197. San Diego is second with 93.

   b. Los Angeles also has the highest number of customers that Joined with 18. San Diego and San Francisco comes second with 7

   c. San Diego has the highest Churn with 185 while Lost Angeles is second with 78. San Fansisco is third with 31 while San Jose is 29

   d. While San Diego and San Fracisco has the highest number of customers, they also have the highest churn rate (especially San Diego.)

   e. There is clearly a market for the service especially at Los Angeles and San Diego but the churn rate in those two states are way too high.

I then went further to analyse the two cities with the highest churn numbers and the following discoveries were made:
    
a. The biggest category for the churn rate in San Diego is 'Competitor' with 52.

b. The biggest reason for the churn rate in San Diego is that 'competitor made a better offer' with 146. This second reason 'Don't know' is 15.

c. Like San Diego, 'Competitor' is the biggest category for Los Angeles but with 39, followed by price with '13.'

d. 'Competitor had better devices' is top for Los Angeles with 15 while 'Competitor' offered higher download speed' is second with 9.

Recommendation: Clearly Competition is the biggest reason for the churn rate in these two cities. This service has to offer better services than the competition. For San Diego, 'Competitor made better offer' is biggest reason people are leaving. The service needs to examine its competition and the offers they make and try to match or better them.

5. Customers with no offer are leaving the most. The number is 1051. Offer E is second with 426. Customers with No offer are also staying the most. So having no offer might not be a significant determinant of Churn rate. However, Offer E and Offer A tell an interesting story. Offer A has the lowest churn number with 35 while they have the 3rd highest stay number with 485. Clearly those with this offer are loyal. Offer E however, has the lowest stay number with 204 and the 2nd highest churn number with 426. Offer E has more people leaving than staying.

Recommendations: Offer A should be offered more and promoted to new users. While Offer E should be taken off the market or modified to make it more attractive.

6. There are five distinct info in the churn category number, the highest being 'Competitor' with 841, followed by 'Dissatisfaction' with 321 The third is 'Attitude' with 314. Drilling down to 'Churn Reason', 'Competitor had better devices' is the top reason with 313, followed by 'Competitor made better offer' with 311. The third is 'Attitude of support person with 220 people giving this reason for leaving.
However, 'Don't Know' is 4th with 130. This is a very high number of customers that left and it is important to get more information on what might have caused them to leave the service.

Recommendation: Like stated before, service must be improved on. better devices and better offers must be made (especially Offer A as stated above and offer E to be improved upon or taken off the market). Also, as recommended before, better devices must be offered especially the fibre optic device that must be improved on to beat the competition. Worryingly, attitude of support person is high on the list with 220 people claiming to have left the service for that. This is especially high in San Diego and Los Angeles area. The company needs to invest in retraining its support staff as they are cursing people to leave the service.

Those who gave 'Don't Know' as their reason for leaving are predominantly in the Month-to-Month category of the Contract. The 'Month-to-month' category has 116 churned customers in the ‘Don’t Know’ category while One year contracts have only 13.

Recommendation: The people who fall into the ‘Don’t Know’ category will most likely stay if they were convinced to take longer contracts. As recommended before, a reward system for customers who take longer contracts should be set in place.
