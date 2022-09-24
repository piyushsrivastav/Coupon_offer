# Coupon_offer
### **Objective** 
The objective is to predict whether or not the the grocery stores will be offering the discount coupons for a given customer.  
### **Domain** 
Retail, Marketing

### Data Description
Income: Customer's yearly household income
Kidhome: Number of children in customer's household
Teenhome: Number of teenagers in customer's household
Recency: Number of days since customer's last purchase
MntFruits: Amount spent on fruits in last 2 years
MntMeatProducts: Amount spent on meat in last 2 years
MntSweetProducts: Amount spent on sweets in last 2 years
NumWebVisitsMonth: Number of visits to company’s website in the last month
AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
Coupon: Classify whether the customer is offered a coupon (target).

### Coupon Offering Classification
Happy-Mart.com is one of the famous online grocery stores operating all over Europe. They have grown their business exponentially during the pandemic. They now want to offer some discount to their customers who have ordered groceries online most frequently. They have thought of offering a 25% discount(through a coupon) to their customers who are ordering groceries online from their stores frequently.


![image](https://user-images.githubusercontent.com/92087972/192085713-9da6790d-ecc9-49bf-9628-b419d920a030.png)



### Overall, Final evaluation of the model
#### Loss: 0.4180299639701843
#### Accuracy: 0.8370535969734192
### Training and validation loss:
![image](https://user-images.githubusercontent.com/92087972/192085599-f838efae-f212-4ffc-9e78-36d6b14eb4b1.png)
![image](https://user-images.githubusercontent.com/92087972/192085611-001400f7-8189-4ac4-9980-9e91afe50896.png)


### Classification Metrics
![image](https://user-images.githubusercontent.com/92087972/192085645-4f947481-58ad-45fb-9a8a-896b12fdb855.png)

### Conclusions
##### After Upsampling the precision has increased for each class, but recall remains the same.
##### Further fine tuning can improve the results better
