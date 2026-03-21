**CUSTOMER RETENTION & CHURN ANALYTICS**
<img width="833" height="469" alt="image" src="https://github.com/user-attachments/assets/dcf983f1-67fa-4637-91ce-702a051a897b" />

*Tech stack*
- Microsoft Excel (Power Query)
- Microsoft Power BI (Power Query, DAX & Measures, Data Visualisation)

**Business Problem**

Customer churn is a major challenge for subscription based businesses, as losing customers directly impacts revenue and growth. Understanding why customers leave, identifying high-risk segments and uncovering patterns in behavior and engagement is critical for building effective retention strategies.

**Objective**

The goal of this project is to:
- Identify key factors contributing to customer churn.
- Analyse customer engagement and subscription patterns.
- Provide actionable insights to improve customer retention.

**Key Analysis Performed**

- Cleaned and transformed raw data in Microsoft Excel to ensure accuracy and consistency: Used Power Query to trim data, replace values and change data types. The date columns had inconsistencies, while other rows started with the year, the others started with the month or day. I used a custom column to fix that.
- Conducted exploratory data analysis (EDA) to identify trends and patterns.
- In Power BI, I created a churn rate measure by firtly creating two other measures called Total Customers and Churned Customers. Then I used the formula Churned Rate = Churned Customers/ Total Customers.
- Built an interactive dashboard to visualise key metrics.

**Key insights**

- The Standard subscription plan has the highest churn rate, suggesting that customers in this tier may not be receiving enough value relative to its price. While the Premium plan performs better, the Basic plan shows the lowest churn, indicating that customers at the lower price tier may have clearer expectations or perceive better value for money.
- Certain customer regions were more at risk than others, the UK showed a high churn rate.
- Customers usually stay for about 97 days which is equivalent to about 3 months, so the customers are not sticking around. This suggests that customers are not finding sufficient long term value in the product, leading to quick disengagement.
- There is no relationship between the customer churn rate and the customer support calls, so, the customer support calls are mostly likely not the reason behind the churning.

**Recommendations**

- We should improve onboarding, and reevaluate the value proposition of the Standard plan by either enhancing its features or adjusting its pricing to better align with customer expectations.
- Track early signals such as low usage, declining engagemnet or inactivity within the first 60 days to target customers at risk of churning, we can try to send them usage reminders.
- Target the UK since it has the highest churn rate with pricing adjustments, tailored retention campaigns, and maybe with some feature adaptations.
- Encourage at-risk Standard plan users to either downgrade to Basic or upgrade to Premium before they churn.



*This analysis demonstrates how data can be used to:*


*- Support data-driven decision making*

*- Improve customer retention strategies*

*- Enhance business performance*
