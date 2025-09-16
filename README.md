# Credit Risk Analysis: A Proactive Approach to Minimizing Defaults

## Interactive Dashboard

The final output of this project is a two-page interactive dashboard built in Tableau. This dashboard identifies high-risk customer segments and allows users to explore the key behavioral and demographic drivers of credit card default.

### [Click Here to View the Interactive Dashboard on Tableau Public](https://public.tableau.com/views/Book1_17453102811930/ExecutiveSummary?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 1. Project Overview
This project analyzes a dataset of 30,000 credit card clients in Taiwan to understand the primary factors leading to default. With a **default rate of 22.12%**, the goal was to identify high-risk customer segments and provide data-driven recommendations to the business to help reduce financial losses. The analysis was conducted using Python for data cleaning and preparation, and Tableau for creating a comprehensive, interactive dashboard.

## 2. The Business Problem
In the financial industry, credit card default is a significant source of financial loss. This project aims to answer three key business questions:

**1. What customer details (like age, payment history, etc.) are the best signs that a customer will default?**
**2. Which groups of customers have the highest risk of defaulting?**
**3. What actions can the company take to lower the number of defaults?**

## 3. The Dataset
The analysis uses the publicly available "Default of Credit Card Clients Dataset" from the UCI Machine Learning Repository.
* Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients)
* Content: The dataset contains 30,000 customer records and 24 features, including demographic information, credit limit, historical payment status, bill amounts, and payment amounts.

## 4. The Process

My approach involved a two-stage analytical process, moving from technical exploration to business-focused communication.

1.  **Data Cleaning & Exploratory Analysis (Python):**
    * I began by loading the dataset into a Jupyter Notebook. Using the **Pandas** library, I cleaned the data to ensure it was accurate and consistent. This included fixing messy categories in the `Education` and `Marriage` columns.
    * After cleaning, I performed an initial **Exploratory Data Analysis (EDA)** using **Matplotlib** and **Seaborn**. I created several charts to get a first look at the data's patterns, understand the distribution of key variables like age and credit limit, and form my initial hypotheses about the main drivers of default.

2.  **Interactive Dashboarding for Business Insights (Tableau):**
    * With the initial findings from my Python EDA, I then moved to **Tableau** to build a comprehensive, interactive dashboard.
    * The goal of this stage was to take the initial insights and present them in a way that is clear, professional, and easy for a business user to understand and explore. I built 8 distinct charts and assembled them into two dashboards: an **Executive Summary** and a **Financial Deep Dive**.

## 5. Key Findings & Insights

The analysis uncovered several clear insights into what drives a customer to default:

* **Finding #1: Recent Behavior is the Biggest Clue.** More than anything else, a customer's recent actions predict their future behavior. Being just **one month late on a payment is the most powerful warning sign** that a customer is in trouble.

* **Finding #2: Financial Stress Has Early Warning Signs.** Before they miss a payment, customers often show clear signs that they are struggling financially. The two biggest signs I found were:
    * Using almost all of their available credit limit.
    * Consistently failing to pay off their bill, which causes their debt to grow over time.

* **Finding #3: Demographics Provide Extra Context.** While behavior is the main story, some groups are slightly more at risk. The data showed this includes customers who are **younger**, **single**, or have a **high school education**.

## 6. Business Recommendations

Based on these findings, I recommend a proactive, three-part strategy to minimize defaults:

1.  **Intervene Early:** The company should reach out with helpful, solution-focused options (like a flexible payment plan) the very first time a customer misses a payment.
2.  **Monitor for Financial Warning Signs:** Proactively identify customers who are using almost all of their credit and offer them support *before* they are late.
3.  **Create a Smarter Start for New Customers:** For new customers in higher-risk groups, the company can provide financial literacy resources and start them with a lower, safer credit limit that can be increased after a history of good payments.

## 7. Technology Stack

* **Data Cleaning & Exploratory Analysis:** Python (Pandas, Matplotlib, Seaborn)
* **Interactive Visualization & Dashboards:** Tableau Public

---

Thank you for taking the time to check out my project! I enjoyed the challenge of taking this project from a raw CSV file to a complete, interactive dashboard. My goal was to not just analyze the data, but to tell a clear story that could lead to real business actions.

I'm always eager to learn and discuss different approaches to solving problems with data. If you have any questions, feedback, or just want to connect, please feel free to reach out!

**[Connect with me on LinkedIn](https://www.linkedin.com/in/praditajeng/)**