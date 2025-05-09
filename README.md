#Customer Satisfaction Prediction Project

**Overview**

Welcome to the Customer Satisfaction Prediction project! This project uses machine learning to predict how satisfied customers are with their tech product support experience. By analyzing a dataset of customer support tickets, we aim to uncover patterns and build a model that predicts satisfaction ratings (on a scale of 1 to 5). Whether you're a data science enthusiast or a business looking to improve customer service, this project offers valuable insights into customer behavior and support trends.

**What’s This Project About?**

We’re working with a dataset of customer support tickets for various tech products, like cameras, smart TVs, and software. Each ticket includes details such as:




Customer info: Age, gender, and email.



Product details: What they bought and when.



Ticket details: Type (e.g., technical issue, billing), subject, priority, and how it was resolved.



Satisfaction rating: How happy the customer was with the resolution (1–5).

**Our goal is to:**





Explore the data to find trends (e.g., common issues or ticket patterns).



Build a machine learning model to predict customer satisfaction.



Visualize key insights, like which factors matter most for happy customers.

**Dataset**

The dataset, sourced from Kaggle (customer_support_tickets.csv), 
contains 
8,469 support tickets with 17 features, 

*including:*





Ticket ID: Unique identifier.



Customer Age/Gender: Demographic info.



Product Purchased: Tech product involved.



Ticket Type/Subject: Nature of the issue.



Ticket Status/Priority: Current state and urgency.



Customer Satisfaction Rating: Target variable (1–5, available for closed tickets).



Resolution Time: How long it took to resolve.

Some fields, like satisfaction ratings, are missing for unresolved tickets, so we’ll handle that during preprocessing.

**Tools & Technologies**





Languages: Python, SQL (for data querying, if needed).



Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.



Environment: Jupyter Notebook, VS Code.



Domain: Data Science, Machine Learning.

**Project Steps**





Data Preprocessing: Clean the data, handle missing values, and encode categorical variables.



Exploratory Data Analysis (EDA): Visualize trends, like common ticket types or satisfaction by gender.



Feature Engineering: Prepare features for modeling, including scaling and encoding.



Model Building: Train a Random Forest Classifier to predict satisfaction.



Model Evaluation: Check accuracy and analyze feature importance.



**Visualizations:**
Create plots to showcase findings, like ticket trends or top products.
Key Findings





Common Issues: Top ticket subjects include refund requests, software bugs, and product compatibility.



Satisfaction Trends: Satisfaction ratings are fairly evenly distributed (1–5), with a mean of ~2.99.



Demographics: Customers aged 31–60 raise the most tickets; gender distribution is balanced.



Top Products: Popular products include Canon EOS, GoPro Hero, and LG Smart TV.



Model Performance: The Random Forest Classifier achieves decent accuracy (exact value depends on the run, typically ~70–80%).

Visualizations

The project includes plots like:





Ticket trends over time (line chart).



Satisfaction distribution (histogram).



Top products by gender (bar charts).



Feature importance for the model (horizontal bar chart).

