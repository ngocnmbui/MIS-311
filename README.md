# Project 1: Predicting Total Overhead Cost from Delivery Variables
## Context and Objective
The analysis aimed to examine how specific delivery-related variables influence total overhead costs. The dataset includes information on the number of delivery days, number of deliveries, miles traveled, delivery time, and the weight of deliveries, with the total overhead cost as the dependent variable.
## Key Variables:
* Total Overhead Cost: Cost associated with delivery operations (dependent variable).
* Delivery Days: Number of days taken for delivery operations.
* Deliveries: Total number of deliveries made.
* Miles: Total miles traveled during deliveries.
* Delivery Time (Minutes): Total minutes spent on deliveries.
* Weight of Delivery (lbs): Total weight of goods delivered.
## Analysis Findings:
The estimated overhead cost per delivery can be found using the equation below: 

Overhead Cost per Delivery = 14.45 + 0.46* Miles + 1.89 * Time	

![image](https://github.com/user-attachments/assets/f481b62c-86ff-47b7-9eca-b89eb3c87d6e)

Figure.1. Scatterplot showing strong positive correlation of actual overhead cost vs. estimated overhead cost per delivery
The regression analysis revealed the following key insights:
* Miles per Delivery: Positive coefficient (0.4548), indicating that increased mileage per delivery notably increases overhead costs.
* Time per Delivery: Highly significant positive coefficient (1.8805), demonstrating that the duration of each delivery has the strongest positive impact on overhead costs.
* Weight per Delivery: Negative and statistically insignificant coefficient (-0.0023), suggesting that weight does not significantly predict changes in overhead costs.
## Conclusion and Implications:
The results highlight that optimising delivery times and minimising miles traveled per delivery could significantly reduce overhead costs. Weight per delivery appears to have minimal impact and may not require immediate operational attention. Businesses can leverage these insights to enhance cost efficiency through targeted delivery management improvements.
