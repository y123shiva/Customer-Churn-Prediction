# Customer-Churn-Prediction

A Satisfied Customer Is The Best Business Strategy Of All

# What Is Customer Churn ?
Customer churn or customer attrition is the phenomenon where customers of a business no longer purchase or interact with the business. A high churn means that higher number of customers no longer want to purchase goods and services from the business.

Customer churn is one of the most important metrics for a growing business to evaluate.While it's not the happiest measure, it's a number that can give your company the hard truth about its customer retention.

Customer churn is the percentage of customers that stopped using your company's product or service during a certain time frame.

It's hard to measure success if you don't measure the inevitable failures, too. While you strive for 100% of customers to stick with your company, that's simply unrealistic. That's where customer churn comes in.

# Usually Company,calculates the churn rate as the percentage of customers lost that quarter. From which you can get the below results:-
1. The number of customers lost.
2. The value of recurring business lost.
3. The percentage of recurring value lost.

# How We Can Calculate Customer Churn Rate ?

Customer churn rate is the number of customers you have lost divided by the total number of customers. To have an estimate you can segment your customers on the basis of the frequency of their purchase.

# Customer Churn Rate = No. of Customers lost/Total no. of customers (Period) x 100

# Reason To Analysis Customer Churn 
1. Before you want to find solutions to improve your churn rate you should know what is causing it in the first place.
2. If you have implemented a solution to reduce the churn then you should know if its working or not.

# What Happens When The Churn Rate Increases ?
When the churn rate increases it will be a negative impact on a business:
1. Cost of acquiring new customers is significantly higher than retention costs.
2.The rate of selling to an existing customer is at an average 60% higher than selling to a customer who is not familiar with your brand.
3.Existing customers, when satisfied are an excellent source for brand promotions through the organic spread of “word of mouth”. In other words, they become your brand promoters and recommend your brand to others, thereby increasing your overall customer base without you having to spend more on customer acquisition.

# How To Reduce Customer Churn ?

We can do the following things.
1. Focus your attention on your best customers.
2. Analyze churn as it occurs.
3. Show your customers that you care.
4. Ask your customers the right questions.
5. Offer more than usual to your loyal customers.

In this Repositary, I will try to do detailed Exploratory data analysis(EDA) on Credit Card Dataset with Visualization. Here, I will try to do univariate and bivariate at the same time.Let's extract different insights from data that help to find the behavior of the churned customer. From which we can provide them better services and turn customers' decisions in the opposite direction. Also,my goal is to predict customer churn from the dataset and gain some insights on how the bank can reduce the customers who have churned.

# About Of The Dataset :-

1.CLIENTNUM - Client number. Unique identifier for the customer holding the account.
2.Attrition_Flag - Internal event (customer activity) variable - if the account is closed then 1 else 0.
3.Customer_Age -Demographic variable - Customer's Age in Years.
4.Gender - Demographic variable - M=Male, F=Female.
5.Dependent_count - Demographic variable - Number of dependents.
6.Education_Level - Demographic variable - Educational Qualification of the account holder (example: high school).
7.Marital_Status - Demographic variable - Married, Single, Divorced, Unknown.
8.Income_Category - Demographic variable - Annual Income Category of the account holder.
9.Card_Category - Product Variable - Type of Card (Blue, Silver, Gold, Platinum).
10.Months_on_book - Period of relationship with bank.
11.Total_Relationship_Count-Total no. of products held by the customer.
12.Months_Inactive_12_mon - No. of months inactive in the last 12 months.
13.Contacts_Count_12_mon-No. of Contacts in the last 12 months.
14.Credit_Limit-Credit Limit on the Credit Card.
15.Total_Revolving_Bal-Total Revolving Balance on the Credit Card.
16.Avg_Open_To_Buy-Open to Buy Credit Line (Average of last 12 months).
17.Total_Amt_Chng_Q4_Q1- Open to Buy Credit Line (Average of last 12 months).
18.Total_Trans_Amt-Total Transaction Amount (Last 12 months).
19.Total_Trans_Ct- Total Transaction Count (Last 12 months).
20.Total_Ct_Chng_Q4_Q1-Change in Transaction Count (Q4 over Q1).
21.Avg_Utilization_Ratio-Average Card Utilization Ratio.

# Steps followed in  process of Customer-Churn Predictions:

1. Import The Libraries
2. Loading The Dataset.
3. Meta Info Of The Dataframe
4. Checking NAN Values.
5. Finding The Duplicate Records.
6. Basic Statistics.
7. Detecting The Outliers.
8. EDA & Visualization On Numerical Analysis.
9. EDA & Visualization On Categorical Analysis.
10. Visualize The Correlation Between Dependent And Independent Features.
11. Encoding The Features.
12. Scaling The Features.
13. Split Train & Test.
14. Visualize Model Score.
15. Hyper Parameter Tuning.
16. Checking The Best Estimators.
17. Train The Model With Best HyperParameters.
18. Plotting The Confusion Matrix.
19.Feature Importances.
20. Conclusion.

# Conclusion

1. There are 16.07% of customers who have churned.

2. The proportion of gender count is almost equally distributed (52.9% male and 47.1%) compare to proportion of existing and attributed customer count (83.9% and 16.1%) which is highly imbalanced.

3. The proportion of attrited customers by gender there are 14.4% more male than female who have churned.

4. Customers who have churned are highly educated - A high proportion of education level of attrited customer is Graduate level (29.9%), followed by Post-Graduate level (18.8%).

5. A high proportion of marital status of customers who have churned is Married (43.6%), followed by Single (41.1%) compared to Divorced (7.4%) and Unknown (7.9%) status - Marital stuats of the attributed customers are highly clustered in Married status and Single.

6. As you can see from the proportion of income category of attrited customer, it is highly concentrated around 60K−80K income (37.6%), followed by Less than " 40Kincome(16.7120K + (11.5%). I assume that customers with higher income doesn't likely to leave their credit card services than meddle-income customer.

