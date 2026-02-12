
📊 Customer Segmentation Using RFM Analysis

📌 Project Overview
This project performs Customer Segmentation using RFM (Recency, Frequency, Monetary) Analysis on the UCI Online Retail Dataset. The goal is to analyze customer purchasing behavior, group customers into meaningful segments, and generate actionable marketing insights.By leveraging data analytics and machine learning techniques, the project helps businesses better understand their customers and design targeted marketing strategies.

🎯 Objectives
Analyze customer behavior based on:

- Recency: How recently a customer made a purchase

- Frequency: How often they made purchases

- Monetary: How much money they spent

- Assign RFM scores to each customer

- Segment customers into groups using clustering techniques

- Visualize customer segments using bar charts and heatmaps 

- Provide practical marketing recommendations for each segment

📂 Dataset

Dataset Used: Online Retail Dataset (UCI Machine Learning Repository). The dataset contains transactional data from an online retail store, including:
Invoice details, Product information, Quantity purchased, Customer ID, Transaction dates


🛠 Tools and Libraries

Python, Numpy, Pandas, Matplotlib, Seaborn, Scikit-learn 


🔍 Methodology
1. Data Preprocessing : Cleaning missing and inconsistent values, removing duplicate records and formatting date and numerical columns

2. Feature Engineering: Calculating RFM metrics(receency,frequency and monetary value) for each customer:

3. Scoring and Segmentation: Assigning RFM scores, normalizing features, and applying clustering algorithms to group customers

4. Visualization: Visualizing customer segments using bar chart and heatmap


📈 Key Outputs

- RFM score table for all customers

- Customer clusters with similar behavior

- Visual chart and heatmap


💡 Marketing Recommendations

Based on the segmentation results, the project suggests simple and practical marketing actions for each cluseter such as:

1. Customers in Cluster 1: Loyal and best customers since they have High R, F, M Scores. We can provide them with the following:
- Special deals just for them.
- Let them see new products before anyone else.
- Points programs, freebies, or thank-you gifts.
- Suggest products based on their purchase history.
- Invitations to exclusive online or in-person events.
  
2. Customers in Cluster 2: moderate and regular customers since they have medium R, F, M Scores. We can provide them with the following:
- Give them a deal if they buy multiple products together.
- Encourage bigger or more frequent purchases.
- Send gentle reminders about products they liked or bought before.
- Ask what would make them buy more and show you value their opinion.

3. Customers in Cluster 0: Inactive and at-risk customers since they have very low R, F, and M Scores. We can provide them with the following:
- You can send them a re-engagement email, with a special discount or gift.
- Offer a one-time, big discount or free shipping.
- Encourage them to update their preferences or interests.
- Showcase bestsellers or new arrivals to get their attention.

⭐ Future Improvements

- Integrate more advanced clustering techniques
- Build an interactive dashboard
- Deploy as a web application
