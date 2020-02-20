# Retail Analytics 

### Key Metrics to get insights of business performance, Customer Segmentation, Customer Lifetime Value Prediction
 
In this project I have used online dataset from UCI Machine Learning Repositories.
Link to Repository - https://archive.ics.uci.edu/ml/datasets/online+retail

## Objective and Approach:

## 1) Business Performance
### **To identify Business Key Metrics and evaluate the performance over years**

**Approach**

Worked on deriving the following metrics :
* Revenue
* Monthly Active Customers
* Monthly Order Count
* Average Revenue Per Order 
* New customer Ratio
* Monthly Retention Rate

## 2) Understanding Customers
### **Perform Customer Segmentation group customers with similar behaviour to analyze the segments,understand customer behaviour and to recommend effective marketing startigies for each segment**
I
**Approach**

I have used RFM Clustering using KMeans and identified three segments :

* **High-Value** : Based on our segmentation these are the customers who purchased recently. They Generate more revenue to the company and are also frequent buyers. This segment contains our **Champions** or to say our **loyal customers**. They are precious for our business and we should keep in touch with them.

* **Mid-Value** : This segment has clustered users that have got items somewhat recently are moderately frequent generating moderate revenue. These customers will comprise of new customers as well who have just started buying from us. This segment will also comprise of **potential loyalist** .

* **Low-Value** : This is the most risky segment for the company as it comprises of **Lost Customers** or **Hibernating** Customers. The customers and in this group are not active as they didnt buy anything recently, not making much revenue for the company and do not buy frequently. 

**Recommendations**

* **High-Value** : Take feedbacks from the customers (use to improve business) . As this group is the most profitable for the company asking for their prefernces and personalize offers to keep them happy and satisfied. Focusing to retain them as loyal customers over years is top priority.

* **Mid-Value** : As this group comprises of new customers as well , it is important to keep them engaged. Send incentivized offers to get more orders from this group.

* **Low-Value** : This group has valuable customers who stopped transacting a long time ago. An attemp to re-engage them by sending crazy lucrative offers to get them back. Make them feel valued by sending personalized recommendations and offers based on their past purchase data

