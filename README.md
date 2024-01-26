# Campaign-Analysis-with-A/B-Testing


![image](https://github.com/olajumokeabe/Campaign-Analysis-with-A-B-Testing/assets/125363157/2fe8bfef-0ff1-499f-8c76-f47dcf355a78)


## Table of Contents
• Introduction

• Steps Taken

• Insight

• KPI Insight

• Conclusion

# Introduction

A/B testing, also known as split testing, refers to a randomized experimentation process wherein two or more versions of a variable (web page, page element, etc.) are shown to different segments of website visitors at the same time to determine which version leaves the maximum impact and drives business metrics. [Read More about A/B Testing here](https://vwo.com/ab-testing/#:~:text=A%2FB%20testing%2C%20also%20known,impact%20and%20drives%20business%20metrics).

A/B testing helps in finding a better approach to finding customers, marketing products, getting a higher reach, or anything that helps a business convert most of its target customers into actual customers.

__Below are all the features in the dataset:__

Campaign Name: The name of the campaign

Date: Date of the record

Spend: Amount spent on the campaign in dollars

of Impressions: Number of impressions the ad crossed through the campaign

Reach: The number of unique impressions received in the ad

of Website Clicks: Number of website clicks received through the ads

of Searches: Number of users who performed searches on the website

of View Content: Number of users who viewed content and products on the website

of Add to Cart: Number of users who added products to the cart

of Purchase: Number of purchases

__Two campaigns were performed by the company:__

• Control Campaign

• Test Campaign

## Steps taken:
***1.	Understanding the Data:***
Explore the contents of both files. Understand the structure, column names, and the kind of data they contain.

***2.	Define the Hypotheses:***
Clearly state what I want to test. I was interested in testing if there's a significant difference in a specific metric (e.g., conversion rates) between the control and test groups.

***3.	Identify Your Key Metrics:***
Determine the key performance indicators (KPIs). This includes click-through rates, conversion rates, cost per click and return on investment

***4.	Clean and Preprocess Data:***
Clean the data to handle missing values, outliers, or any other issues to ensure that the data is in a format suitable for analysis.

***5.	Combine Data:***
Merge the control and test datasets into a single dataset. Create a new column to indicate whether each row is from the control or test group.

***6.	Perform Statistical Analysis:***
Use statistical tests to compare the key metrics between the control and test groups. Common tests include t-tests for continuous variables and chi-square tests for categorical variables. t-tests was adopted for the analysis.

***7.	Calculate P-Values:***
Calculate p-values to determine the statistical significance of the observed differences. A low p-value (typically below 0.05) suggests that the observed differences are unlikely due to random chance.

***8.	Interpret Results:***
Based on the p-values, determine whether there's a statistically significant difference between the control and test groups. Interpret the results in the context of your hypotheses.

***9.	Conclusions:***
Draw conclusions from your analysis. If there's a significant difference, consider the practical significance and make informed decisions based on the results.

***10.	Document and Communicate:***
Document your methodology, results, and conclusions. Clearly communicate your findings, including any implications or recommendations.

## Tools used:
•	***Python Libraries:*** Pandas for data manipulation, NumPy for numerical operations, Scipy and StatsModels for statistical tests.

•	***Visualization Tools:*** Matplotlib, Seaborn and plotly for visualizing the data and results.

## Insights
The test campaign got more people to search on the website. It also won when it comes to the number of clicks on the website. However, the audience of the control campaign looked at more content than the test campaign. Even though the control campaign had fewer clicks, people engaged more with it on the website.

Surprisingly, even with fewer clicks, more products were added to the cart from the control campaign. The test campaign spent more money compared to the control campaign. But considering that the control campaign led to more content views and more products added to the cart, it seems like the control campaign is more effective than the test campaign.
The difference in purchases between the two ad campaigns is only around 1%. The control campaign resulted in more sales with less money spent on marketing.

## KPIs Insights
The CTR values range from approximately 4.20% to 8.48%. Higher CTR values generally indicate a higher proportion of clicks relative to the number of impressions.

Conversion Rate ranges from around 5.30% to 11.09%. A higher Conversion Rate is generally desirable, as it indicates a higher percentage of users completing the desired action.

The CPC values range from approximately 0.22 to 0.63. Lower CPC values suggest more cost-effective advertising, as it costs less on average for each click.

The ROI values are negative, indicating a negative return on investment. This suggests that the costs incurred (negative ROI) outweigh the benefits. A positive ROI is generally desired, indicating that the investment is profitable.

## Conclusion

The A/B testing analysis reveals a non-significant difference between the two campaigns, as indicated by a p-value less than 0.05. This implies that the null hypothesis is not rejected, reinforcing the similarity between the test and control groups.

Examining specific metrics, both campaigns demonstrate comparable conversion rates, while the test group exhibits a higher Click-Through Rate (CTR), signaling heightened user engagement with ads. On the other hand, the control group boasts a slightly superior Conversion Rate, indicating a greater likelihood of purchases post-click.

Furthermore, the test campaign showcases a lower Cost Per Click (CPC), suggesting cost-effectiveness in generating more clicks and potential leads within the budget. This, in turn, contributes to a higher anticipated return on investment (ROI), promising profitability by surpassing expenses.

Delving into sales and engagement outcomes, the control campaign emerges as the frontrunner. It yields more product views, resulting in a higher number of items in the cart and, consequently, more sales. However, the test campaign excels in the conversion rate of products in the cart, making it particularly effective for generating sales based on viewed and carted products.

In light of these findings, a strategic approach can be adopted. The test campaign proves advantageous for marketing specific products to a targeted audience, leveraging its high conversion rate. Meanwhile, the control campaign is well-suited for marketing multiple products to a broader audience, harnessing its ability to drive overall sales. These insights provide valuable guidance for optimizing future advertising strategies.

