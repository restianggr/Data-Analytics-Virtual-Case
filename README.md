# PwC Virtual Case Experience
We aim to build innovative technology solutions that differentiate us from our competitors and digitise the business. Part of that included a strategic decision to invest in upskilling programmes so our people could learn how to use digital tools for data visualisation as well as automation, data cleansing and more.

Our Digital Accelerator programme is an internal chance that takes groups of our employees out of their day jobs and puts them through trainings that teaches them skills in technology such as automation, machine learning, design thinking, and digital storytelling.

---
# HR Data Analysis: Diversity and Inclusion

## Business task
Assist HR at the telecom client in improving gender balance at the executive management level, addressing challenges in diversity and inclusion. PwC Switzerland aims to provide support to clients in cultivating diverse and inclusive workforces, recognizing these as essential business imperatives. Achieving this goal involves overcoming practical challenges within the organizational context. The purpose of this analysis is to:
- Define relevant key performance indicators (KPIs) related to gender balance and diversity in hiring, promotion, performance, and turnover.
- Provide visual representations of HR data.

The following measures could help to define proper KPIs:
- '#' of men
- '#' of women
- '#' of leavers
- % employees promoted (FY21)
- % of women promoted
- % of hires men
- % of hires women
- % turnover 
- Average performance rating: men
- Average Performance rating: women

---

## Data Preparation

### Data Source

[Pwc Switzerland](https://www.pwc.ch/en/careers-with-pwc/students/virtual-case-experience.html) provided the [dataset](https://github.com/restianggr/Data-Analytics-Virtual-Case/blob/main/Diversity%20%26%20Inclusion/03%20Diversity-Inclusion-Dataset.xlsx) used in this analysis.


### Tools

This analysis employs Power BI Desktop for its execution.


### Data Cleaning

Data Cleaning for the dataset was done in Power Query as follows:
- Unnecessary rows were filtered
- Each of the columns in the table were validated to have the correct data type
- Verifying for duplicate entries and null values

---


## Data Visualization

![Diversity & Inclusion](Diversity%20%26%20Inclusion/Diversity%20%26%20Inclusion.png)

*The visualizations are underpinned by measures formulated in DAX*

### Statistical Findings

- There are ` 205 ` women and ` 295 ` men
- ` 10.1% ` of the overall turnover rate
- Average rating for women is ` 2.42% ` 
- Average rating for men is ` 2.41% `
- Men currently dominate in terms of departures, promotions, and executive levels, each exceeding ` 50% `

---

# Key Findings

- Presently exhibits a slightly greater presence of male employees in comparison to females. This indicates the necessity to emphasize gender balance initiatives, ensuring equitable opportunities for both genders.
- Employees left in FY20 indicates that performance alone may not retain talent. Consider factors like career development, job satisfaction, and work-life balance.

# Recommendations

1. Gender Balance Initiatives: Implement programs to achieve gender balance, providing equal opportunities for both male and female employees.
2. Comprehensive Employee Retention: Recognize that talent retention goes beyond performance alone. Focus on career development, job satisfaction, and work-life balance.
3. Exit Interview Insights: Conduct exit interviews to understand reasons for employee exits in FY20 and adjust organizational strategies accordingly.
4. Engagement and Flexibility: Implement employee engagement programs and offer flexible work arrangements to enhance workplace satisfaction.
5. Continuous Monitoring: Regularly monitor and adjust initiatives based on feedback and evolving organizational needs.
   
---

# Customer Retention Analysis
Following the presentation of a Power BI dashboard, I am developing another dashboard focused on customer retention using Tableau. The client had previously attempted to analyze customers with Excel, but it wasn't successful. They want to gain more insights about their customers and present the information in a clear way that management can easily understand.

---

## Data Preparation

### Data Source

[Pwc Switzerland](https://www.pwc.ch/en/careers-with-pwc/students/virtual-case-experience.html) provided the [dataset](https://github.com/restianggr/Data-Analytics-Virtual-Case/blob/main/Customer%20Retention/02%20Churn-Dataset%20(1).xlsx) used in this analysis.


### Tools

Excel: Data cleaning

Tableau: Data visualizing

### Data Cleaning

- Creating a new row for the subscription period.
- Replacing the values of Senior Citizen from 0,1 to No,Yes.

---

## Data Visualization

![Diversity & Inclusion](https://github.com/restianggr/Data-Analytics-Virtual-Case/blob/main/Customer%20Retention/Dashboard%201%20(1).png)

*[View the live dashboard here](https://public.tableau.com/views/CustomerRetention_17059060782300/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link)*

### Statistical Findings

- There are ` 7043 ` total customers.
- ` 26.54% ` of the churn rate.
- The customers with subscriptions  `> 12 months` are the highest.
- The most commonly chosen contract type is ` month-to-month `.
  
---

# Key Findings

- Customers with a ` Two-Year ` contract type have long-standing relationships with the company, whereas the majority of those with a ` Month-to-Month ` contract type recently joined.
- The company faces a risk of losing recently acquired customers if they opt for a ` Month-to-Month ` contract type based on the analysis results.
- A total of 7043 customers are at the risk of churn, constituting a churn rate of 26.54%.
- The majority of customers who churned did not subscribe to Online Security, tech support, or Phone Services.
- Many customers experienced issues with Fiber Optic. Specifically, 41.89% of the churned customers were utilizing Fiber Optic for their Internet Services.

# Recommendations

1. Promote Long-Term Contracts: Encourage customers to opt for Two-Year contracts by highlighting the benefits of long-term commitments, such as potential cost savings and stable service.
2. Incentivize Contract Renewals: Introduce incentives for customers with Month-to-Month contracts to consider longer-term commitments. This could include discounts, special offers, or additional services to enhance customer loyalty.
3. Targeted Retention Strategies: Implement targeted retention strategies for the 7,043 customers identified as being at risk of churn. Offer personalized promotions, discounts, or improved services to retain their loyalty.
4. Promote Additional Services: Emphasize the importance of Online Security, tech support, and Phone Services to customers. Consider creating bundled packages to make these services more appealing.
5. Improve Fiber Optic Services: Address and resolve issues related to Fiber Optic services to reduce customer churn. Consider investing in infrastructure improvements, customer support enhancements, or communication campaigns to reassure customers.
