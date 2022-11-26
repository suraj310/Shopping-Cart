# Shopping-Cart

 Name - Suraj Kumar , 
 College - IIIT Ranchi , 
 Roll No:- 2019UGCS027R ,
 Year of Passing - 2023 ,
 Phone number - 8294083788 ,
 Email address - suraj.btech.cs19@iiitranchi.ac.in 


A shopkeeper sells products. Some products are eligible for GST(Goods and Service
Tax) and some are not. To attract customers the shopkeeper has offered a 5% discount
for products whose unit price is Rs. 500 or more.
A customer has added below products to basket

# Basket
|   | Product | Unit Price in Rupees | GST in % | Quantity |
|---|---------|----------------------|----------|----------|
| 1 | Leather Wallet | 1100 | 18 | 1|
| 2 | Umbrella | 900 | 12 | 4|
| 1 | Cigarette | 200 | 28 | 3|
| 1 | Honey | 100 | 0| 2

PROBLEM TO SOLVE
Create a suitable data structure to hold product details in the basket as per above table.
1. Identify the product for which we paid maximum GST amount
2. Calculate the total amount to be paid to the shop-keeper

#solution

We created a structure in that we have taken all the product details and the structure name is cart.
After that we had taken vector of type cart named items and then taken all the values given in the table.
We then updated the unit price according to the discount condition given in the description.
We then calculated the maximum gst amount for every product and then stored it in a variable called maxi_gst_pro.
and taken the name in max_gst_pro_name and calculated the total amount by adding all values of curr_product. 
