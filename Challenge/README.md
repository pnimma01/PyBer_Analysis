# PyBer_Analysis
**PyBer with MatPlotLib**

**Note:**
I worked with Aman Gill for this challenge. We followed pair-programming methodology and the code and readme were co-created.

# **PyBer Analysis**

## **Project Overview**

## **Overview of the analysis:**
We will be analyzing the ride share data based on the following type of rides:
1. Urban
2. Suburban
3. Rural

Here is the summary of  Average Fare by City Type: ![Average Fare by City Type](https://github.com/pnimma01/PyBer_Analysis/blob/b66012ac31ed6c5dbc9ff775542ca501bb5a81f9/Challenge/Resources/Average%20Fare%20Group%20By.png)

Total Fare by City Type:  
![Total Fare by City Type](https://github.com/pnimma01/PyBer_Analysis/blob/b66012ac31ed6c5dbc9ff775542ca501bb5a81f9/Challenge/Resources/Challenge_fare_summary.png)

## **Results**

After merging and summarizing the data using groupby, we find out that:
1. Rural cities have lowest and Urban cities have highest number of drivers and number of rides
2. Rural areas also have the highest average fare, either by ride or by driver.
3. However, Revenue (total fare amount) is lowest in rural cities and while it is hishest in urban cities .
4. **One interesting find is thar the average fare per driver is really low in urban cities.**

## **Summary:**

Based on the results, here are our three business recommendations:
1. There are lot more drivers in urban areas as compared to Suburban and Rural areas. Data shows that there is actually shortage of drives in rural areas by 2:1.  It will help if the drivers are moved to Rural and Suburban cities from Urban cities.
2. Gap between average fare per driver is significantly higher than average fare per ride between Urban and Rural cities. This stems from lack of drivers in rural areas. Company can benefit from providing discounts while maintaining driver compensation in rural areas which may increase total rides and attract more drivers.
3. All three city types show consistent variations in fare amount except during the start of summer season in suburban areas. It may make sense to expand services during summer in suburban areas.

### **Challenges encountered:**
1. We could perform a more thorough analysis if the provided data included miles driven and time taken per each ride.
2. More statistics like car maintenance (including gas) per mile or per minute of ride would be helpful in understanding costs incurred during each ride. These numbers will help us get to a profit and loss ratio for each driver.

