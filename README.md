# walmart-sales-analysis
task1=Which store has maximum sale
Store
20    3.013978e+08
4     2.995440e+08
14    2.889999e+08
13    2.865177e+08
2     2.753824e+08
Name: Weekly_Sales, dtype: float64
Task 1 Answer - Store 20 had the highest sales with 3.013978e+08 dollar

Task 2 - Which store has maximum standard deviation i.e., the sales vary a lot. Also, find out the coefficient of mean to standard deviation

Store	Coefficient of Variation
0	1	0.100292
1	2	0.123424
2	3	0.115021
3	4	0.127083
4	5	0.118668

# Maximum CV
	Store	Coefficient of Variation
34	35	0.229681
6	7	0.197305
14	15	0.193384
28	29	0.183742
22	23	0.179721
Task 2 Anwer - Store 14 had the maximum standard deviation in Weekly Sales. Additionally, Store 35 has the maximum coefficient of variation at approximately 0.299

Task 3 - Which store/s has good quarterly growth rate 
![newplot](https://user-images.githubusercontent.com/109465506/186193004-3e367b8b-267f-4253-aeaf-c960a6e0013c.png)

Task 3 Answer - Store 17 and 44 were the only two Wm Stores that have increased their weekly sales during Quarter 3 of year 2012. Other than those two, other stores had decreased their weekly sales. Although Store 4 had the highest weekly sales during this time period, their sales actually went down

Task 4 - Some holidays have a negative impact on sales. Find out holidays which have higher sales than the mean sales in non-holiday season for all stores together
![newplot (1)](https://user-images.githubusercontent.com/109465506/186193261-b119c72f-d0dd-4d19-8c51-2e586ff8b3a0.png)

Occasion
Christmas       0.960833
Labor Day       1.042427
Super Bowl      1.079128
Thanksgiving    1.471273
Name: Weekly_Sales, dtype: float64

Task 5 - Provide a monthly and semester view of sales in units and give insights
![newplot (2)](https://user-images.githubusercontent.com/109465506/186193565-d7bd01fa-8686-4268-8613-963361ad65ea.png)

![newplot (3)](https://user-images.githubusercontent.com/109465506/186193627-7fdc7846-992e-4935-a7ac-40504ad1c3bb.png)

![newplot (4)](https://user-images.githubusercontent.com/109465506/186193731-016c647f-10fb-451c-9af1-a1b7c3fa4d0f.png)
![newplot5](https://user-images.githubusercontent.com/109465506/186193884-48df7e59-dba0-4c2e-be60-0c7c1f1087f0.png)


Task - For Store 1 – Build prediction models to forecast demand (Linear Regression – Utilize variables like date and restructure dates as 1 for 5 Feb 2010 (starting from the earliest date in order). Hypothesize if CPI, unemployment, and fuel price have any impact on sales.) Change dates into days by creating new variable. Select the model which gives best accuracy.

![newplot6](https://user-images.githubusercontent.com/109465506/186194193-de87eea1-bdf4-4abc-9cbc-df4880a1c838.png)

LinearRegression

![newplot7](https://user-images.githubusercontent.com/109465506/186194370-27c2a912-87d2-43f7-83b0-2e528fc2b95a.png)

RSME: 558069.1143546927
Score: 3.70016255950284 %

DecisionTreeRegressor

![newplot8](https://user-images.githubusercontent.com/109465506/186194560-cbbf8b15-76f2-456f-af01-a7e134c343f5.png)

RMSE: 653826.5315906206
Score: 86.9605207434184 %

RandomForestRegressor

![newplot9](https://user-images.githubusercontent.com/109465506/186194777-0a6abdbf-d720-4904-b917-e58f5323e03e.png)

RMSE: 544771.1183605972
Score: 79.24427704024781 %

