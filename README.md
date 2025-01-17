# Pandas-Data-Analyst-Tasks
Set of real world data Analyst tasks completed using the Python Pandas library.

## Background Information
We have of 12 months  sales data during 2019. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc. 

We start by cleaning our data. Tasks during this section include:
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)

Once we have cleaned up our data a bit, we move the data exploration section. In this section we explore 5 high level business questions related to our data:
 1. What was the best month for sales? How much was earned that month? <br/>
![1 results](../main/Results/1.png)
 2. What city sold the most product? <br/>
![1 results](../main/Results/2.png)
 3. What time should we display advertisemens to maximize the likelihood of customer’s buying product? <br/>
![1 results](../main/Results/3.png)
 4. What products are most often sold together? <br/>
![1 results](../main/Results/4.png)
 5. What product sold the most? Why do you think it sold the most? <br/>
![1 results](../main/Results/5.png)

To answer these questions we walk through many different pandas & matplotlib methods. They include:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs


