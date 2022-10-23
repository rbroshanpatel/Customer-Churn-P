# Customer Churn Prediction in Telecom Industry
![image](https://user-images.githubusercontent.com/86373401/197398084-31074885-7da7-41a8-8d41-887664cd8f7c.png)

# What is Customer Churn?
Customer churn is defined as when customers or subscribers discontinue doing business with a firm or service.

Customers in the telecom industry can choose from a variety of service providers and actively switch from one to the next. The telecommunications business has an annual churn rate of 15-25 percent in this highly competitive market.

Individualized customer retention is tough because most firms have a large number of customers and can't afford to devote much time to each of them. The costs would be too great, outweighing the additional revenue. However, if a corporation could forecast which customers are likely to leave ahead of time, it could focus customer retention efforts only on these "high risk" clients. The ultimate goal is to expand its coverage area and retrieve more customers loyalty. The core to succeed in this market lies in the customer itself.

Customer churn is a critical metric because it is much less expensive to retain existing customers than it is to acquire new customers.

To detect early signs of potential churn, one must first develop a holistic view of the customers and their interactions across numerous channels.As a result, by addressing churn, these businesses may not only preserve their market position, but also grow and thrive. More customers they have in their network, the lower the cost of initiation and the larger the profit. As a result, the company's key focus for success is reducing client attrition and implementing effective retention strategy.

# Objectives:
* Finding the % of Churn Customers and customers that keep in with the active services.
* Analysing the data in terms of various features responsible for customer Churn
* Finding a most suited machine learning model for correct classification of Churn and non churn customers.

# Dataset:

https://www.kaggle.com/bhartiprasad17/customer-churn-prediction/data

The data set includes information about:
Customers who left within the last month – the column is called Churn
Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
Demographic info about customers – gender, age range, and if they have partners and dependents

# Implementation:
Libraries: sklearn, Matplotlib, pandas, seaborn, and NumPy

# Few Glimpses:

# 1. Churn Distribution:
![image](https://user-images.githubusercontent.com/86373401/197398295-f7d7499b-fdcb-49fe-ac22-7b557340678f.png)
26.6 % of customers switched to another firm.

# 2. Churn Distribution with respect to gender:

![image](https://user-images.githubusercontent.com/86373401/197398341-075bc727-0958-47ee-986e-b195cb3f393e.png)
There is negligible difference in customer percentage/count who chnaged the service provider. Both genders behaved in similar fashion when it comes to migrating to another service provider/firm.

# 3. Customer Contact Distribution
![image](https://user-images.githubusercontent.com/86373401/197398395-5b947884-1a50-412f-972f-7ca9aa33cd4e.png)
About 75% of customer with month-to-Month Contract opted to move out as compared to 13% of customrs with One Year Contract and 3% with Two Year Contract.

# 4. Payment Method
![image](https://user-images.githubusercontent.com/86373401/197398457-fbb83ebd-55c8-4724-a8ca-8029c26fa0f2.png)

# Customer payment method Distribution with respect to churn
![image](https://user-images.githubusercontent.com/86373401/197398490-c2a1fa5f-ecfa-4c56-9cf0-b1fa7dda4719.png)
Major customers who moved out were having Electronic Check as Payment Method. Customers who opted for Credit-Card automatic transfer or Bank Automatic Transfer and Mailed Check as Payment Method were less likely to move out.

# 5. Internet Services
Several customers choose the Fiber optic service and it's also evident that the customers who use Fiber optic have high churn rate, this might suggest a dissatisfaction with this type of internet service. Customers having DSL service are majority in number and have less churn rate compared to Fibre optic service.
![image](https://user-images.githubusercontent.com/86373401/197398536-763b0947-1c55-4f4f-82a7-a62132226797.png)

# 6. Online Security
As shown in following graph, most customers churn due to lack of online security
![image](https://user-images.githubusercontent.com/86373401/197398581-dfc41db2-2f9f-4ad3-bb7b-59339810c7f5.png)

# 7. Senior Citizen
Most of the senior citizens churn; the number of senior citizens are very less in over all customer base.
![image](https://user-images.githubusercontent.com/86373401/197398612-138f192d-4597-4cd8-82ce-65c761b52870.png)

# 8. Paperless Billing
Customers with Paperless Billing are most likely to churn.
![image](https://user-images.githubusercontent.com/86373401/197398647-2e689b7e-f5ee-4e65-a5ed-c05eb7a8dc07.png)

# 9. Tech Support
As shown in following chart, customers with no TechSupport are most likely to migrate to another service provider.
![image](https://user-images.githubusercontent.com/86373401/197398669-d2752fb3-c51e-4b89-9b10-caf6368efaa7.png)

# 10. distribution w.r.t. Changes and Tenure
![image](https://user-images.githubusercontent.com/86373401/197398711-0589806b-7573-4116-a452-3a235c5a0752.png)
![image](https://user-images.githubusercontent.com/86373401/197398715-8ab99339-f08a-4bc7-bf23-53a4962e1885.png)
![image](https://user-images.githubusercontent.com/86373401/197398720-09c1fd10-f944-4cde-b109-9a27010d6ff8.png)
Customers with higher Monthly Charges are also more likely to churn.
New customers are more likely to churn.

# Machine Learning Model Evaluation and Prediction
* Logistic Regression: 0.791
* Support Vector machine: 0.786
* Random Foresrt: 0.781

# Optimization
We could use Hyperparamete Tuning or Feature enginnering methods to improve the accuracy further.


