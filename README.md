# PCA-Analysis

A1: PROPOSAL OF QUESTION:

"Which factors influence customer churn?"

A2: DEFINED GOAL:

The goal of my data analysis is to identify the key factors that influence customer churn, so the organization can better understand what drives customers to leave. By using PCA, I aim to reduce the complexity of the dataset, focusing on the most important variables that explain the majority of the variance in customer churn. This will help in pinpointing the critical areas where the organization can take action to improve customer retention, such as service quality, pricing, or customer support. Ultimately, the goal is to provide actionable insights that can lead to more effective strategies for keeping customers.

B1: EXPLANATION OF PCA:

PCA analyzes the selected dataset by taking all the variables related to customer churn, like MonthlyCharge, Tenure, and Service Options, and transforming them into a smaller number of new variables called principal components. These components are designed to capture the most important information from the original data while reducing its complexity. The expected outcome is that PCA will help us identify which factors have the most influence on customer churn by highlighting the components that explain the most variance. This makes it easier to focus on the key factors driving churn, simplifying our analysis and helping us make better decisions.

B2: PCA ASSUMPTION:

One assumption of PCA is that the data should have linear relationships, meaning the connections between the variables should follow straight lines. This is important because PCA identifies the main directions of variation in the data, which are best represented as straight lines. If the relationships aren't linear, PCA might not capture the true patterns accurately.
 
C1: CONTINUOUS DATA SET VARIABLES:

- Income
- Outage_sec_perweek
- Tenure
- MonthlyCharge
- Bandwidth_GB_Year

D1: PRINCIPAL COMPONENTS:

I performed PCA on the selected continuous variables related to customer churn, (Income, Outage_sec_perweek, Tenure, MonthlyCharge, and Bandwidth_GB_Year). The first principal component has high loadings for Tenure and Bandwidth_GB_Year, suggesting these variables are key factors in explaining the variance in the data. The matrix helps identify which variables are most influential in driving customer churn, simplifying the analysis by focusing on the most significant components.


D2: IDENTIFICATION OF THE TOTAL NUMBER OF COMPONENTS:

I used the Kiser Criterion and based on the scree plot I generated, which shows the eigenvalues for each principal component, I've determined that the first two principal components are the most significant. These components have eigenvalues greater than 1, which means they capture more variance than any individual original variable. By focusing on these two components, I can simplify my analysis while still retaining the most important information related to customer churn. This approach allows me to reduce the complexity of the data without losing critical insights, making it easier to identify the key factors driving churn.

![image](https://github.com/user-attachments/assets/a9066346-cf40-4b15-8c2e-05c4675c3eb5)

D3: VARIANCE OF EACH COMPONENT:

These values show how much each principal component explains the variation in the data. The components with higher values capture more of the data's differences. From what I can see, the first two components (PC1 and PC2) explain most of the variance, with values of 1.993 and 1.024 respectively. The later components (PC3 to PC5) contribute less to the overall variance, indicating that focusing on the first two components is sufficient to capture the key patterns in the data.


D4: TOTAL VARIANCE CAPTURED BY COMPONENTS:

The first two principal components capture a total variance of 3.0176. This means that these components account for a significant portion of the variability in the dataset, summarizing the most important information in the data while reducing its dimensionality.


D5: SUMMARY OF DATA ANALYSIS:

After analyzing the data using PCA, I found that the first two principal components capture most of the important information in our customer data, explaining a total variance of 5.01. These components represent the main patterns and factors that cause variation in our data. By focusing on these components, I can better understand the key characteristics that affect customer behavior and monthly charges. This simplified view helps me see what's most important without getting overwhelmed by the details, making it easier to make data-driven decisions.






















