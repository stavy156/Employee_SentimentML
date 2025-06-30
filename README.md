# Employee_SentimentML

Overview

This project performs a sentiment analysis on employee communications to assess workplace attitude, engagement, and potential flight risk. The dataset consists of emails with timestamps and sender information. Our objective was to:

Label messages with sentiment (Positive, Neutral, Negative)
Perform exploratory data analysis
Score employee sentiment on a monthly basis
Rank employees based on their scores
Identify at-risk employees
Build a predictive model to forecast sentiment scores

1) Top 3 Positive and Negative Employees (First Month in Dataset)

-Top 3 Positive Employees:

'kayne coulter', 'patti thompson', 'don baughman'

-Top 3 Negative Employees:

'rhonda denton' 'johnny palmer' 'bobette riner'

2)Flight Risk Employees

Employees flagged due to 4 or more negative emails within a rolling 30-day window:

'bobette riner', 'john arnold', 'rhonda denton', 'sally beck', 'patti thompson', 'lydia delgado', 'johnny palmer'

3)Key Insights and recommendations

Sentiment is generally neutral across most employees.
A few employees consistently contribute positive messages—likely strong internal influencers.
Employees with frequent short, negative messages should be monitored closely.
Predictive models using features like message count and average length can approximate sentiment direction, though with modest accuracy.
