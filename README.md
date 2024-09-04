# Customer-Personality-Analysis

Based on the marketing campaign dataset from Kaggle, the project aimed to visulise a model which can help the businesses to examine ideal customers & to identify customers that the
business needs to focus on for better Sales in the future.

The following Hypothesis are proposed:
Hypothesis 1: Customers from Mature Age group with High income have high spending behaviour.
Hypothesis 2: Customers with bigger Family Size have high spending behaviour.
Hypothesis 3: Customers who are associated for a long time with high income have high spending behaviour.
Hypothesis 4: Customers who are highly educated and have high income have highest spending behaviour.
Hypothesis 5: Customers with lower income have higher tendency to accept deals offered by the business.

Data cleaning & loading, Feature Engineering, Attribute correlation & visualistion are the steps performed using python libraries such as pandas, matplotlib, numpy & seaborn.

Based on the hypothesis that were true and looking at the Pearson correletion matrix, it is concluded that spent is highly correlated with Income and Seniority Group.

Four segments are formed to identify the customers that business needs to focus on for better performance:

1. A-List: High Income, Old Customers
2. Attention Required: Below Average Income, New Customers
3. High Potential: High Income, New Customers
4. Likely to Loose: Below Average Income, Old Customers

The Customer Segmentation analysis with respect to Income group and Seniority group provides an overall picture of which segment is to be priorized more and requires attention from the retail store's marketing team.
