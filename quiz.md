This quiz is part of Algoritma Academy assessment process. Congratulations on completing the Programming for Data Science and Practical Statistics course! We will conduct an assessment quiz to test practical programming techniques you have learned on the course. The quiz is expected to be taken in the classroom, please contact our team of instructors if you missed the chance to take it in class.

# Instruction

In this quiz, we will be using a retail dataset. You can get the CSV file stored within the folder under the `retail.csv` file. The data is about a record of a transactions of a retail store specifying several variables. Please take a look at the following glossary for your reference:
- `Order.ID`: Id of order.
- `Order.Date`: Date of Order.
- `Ship.Date`: Date of shipping.
- `Ship.Mode`: type of shipment.
- `Customer.ID`: Id of Customer.
- `Segment` : Customers segment.
- `Product.ID`: Id of Product.
- `Category` : have 3 levels "Furniture","Office Supplies","Technology"    
- `sub.category`: more specific categories
- `Product.Name`: Name of product that was sold.
- `Sales`: How much earning from each sale.
- `Quantity`: Quantity of item sold.
- `Discount`: How much Discount was given for each sale.
- `Profit`: How much can a company earn from each sale.

We will split this quiz into 2 main sections: programming for data science and practical statistics, each assessing the respective knowledge we have learned in the 2 courses.

## Programming For Data Science

1. Among the records, there are some transactions that were bought with the total item quantity of more than 5.  Say we are interested to find out how many of the transactions that generate above-average profit but were sold for the quantity of lesser than 5. Use a conditional subsetting to find out the number of transactions with the given conditions!
  - [ ] 1380
  - [ ] 1793
  - [ ] 2551
  - [ ] 758

2. If you take a look at the `Ship.Mode` column, you will see there are several types of shipping mode. Among all customer segments, which segment made up most of the first-class shipment?
  - [ ] Consumer
  - [ ] Corporate
  - [ ] Home Office

3. If we were to analyze the subcategories within the Office Supplies category, which ones were the 3 most popular subcategories, taking into account the quantity of the item sold in each transaction?
  - [ ] Binder, Paper, Storage
  - [ ] Appliances, Art, Binder
  - [ ] Supplies, Envelopes, Fasteners
  - [ ] Paper, Binder, Art

## Practical Statistics

4. In descriptive statistics, there are two main measurements that are commonly used to describe data distribution: central tendency and measure of spread. Which statistical measure can be used to describe the latter one?
  - [ ] Probability
  - [ ] Mean
  - [ ] Standard Deviation
  - [ ] Correlation

5. Find out the correlation between Sales and Profit of each transaction using the `cor()` function. Based on the correlation between the 2, which of the following statements are true?
  - [ ] As the Sales increase, the Profit gained decreases
  - [ ] As the Sales decreases, the Profit gained decreases
  - [ ] As the Sales increase, the Profit is fixed

6. Consider this case: The retail company would like to apply for a promotion to increase the number of sales. Based on historical record, you know that the monthly Sales population has an average profit of 47,858.35 with a standard deviation of 25,195 and is distributed normally. After the promotion is applied for a month you then calculate the total of Sales to be 81,777. Using 95% confidence interval, perform a significance test on how the promotion affects the number of sales. How would you conclude the test using the given information?
  - [ ] Fail to reject the null hypothesis, the promo does not have a statistically significant impact
  - [ ] Fail to reject the null hypothesis, the promo has a statistically significant impact
  - [ ] Reject the null hypothesis, the promo has a statistically significant impact 
  - [ ] Reject the null hypothesis, the promo does not have a statistically significant impact
