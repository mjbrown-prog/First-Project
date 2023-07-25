***Introduction to Excel for Data Analysis***

**Task 1**

In the Worksheet we were able to create 20 rows of information of employees using the following:

- Employee Id
- Employee Full Name
- Department( Communication Developer, Analyst, Sales, Security, Content Creator)
- Salary($5,000- $25,000)
- Job Type( Freelance, Contract, Part-time)

  

![Employee Png filter](https://github.com/mjbrown-prog/First-Project/assets/64136357/44936fd5-26c7-4400-aac8-585026575cf2)

From the picture above i was able to filter those whose salary is greater than or equal to $10,000 with job type freelance

**Result**

The feedback shows that the Freelancers that fell in this department that got paid of $10,000 is 1 Sales, 1 Developer, 1 Analyst and 1 Communication.

For Worksheet 2

![Employees png Split](https://github.com/mjbrown-prog/First-Project/assets/64136357/aadfd276-b2b5-4495-a6f9-7b1c46ad2429)

From the above worksheet i have to split the employee full name to First name and last name by clixking on text to column the demiliters. 

Worksheet 3

![Employee Png Highest and lowest](https://github.com/mjbrown-prog/First-Project/assets/64136357/ee1f9afd-5679-46ff-8530-3d026a8f9590)

For Worksheet 3, i had to Check for the employees full name which start with "E", Checked for the highest paid and lowest paid and lastly checked for duplicates/

**Result**

- Feedback from that shows Only one employer had their name with a starting letter E hence highlighed in yellow.

- Also, The highest paid and the lowest paid where highlighted as Green and Red respectively.
  
- Moreso, the duplicates where also found which was highlighted in Purple

- Formular Used **Conditional Formatting**
---

**Task 2**

In this Worksheet name Sales we would be working on the following:

- Total Revenue and Profit generated.
- Average revenue and unit sold for every order.
- Total Discount given in $.
- Total Number of sales recorded.
-  Highest Profit.
- Average Revenue From Each Sale of "Paseo".
- Number of Sales made in "Government".
- Number of Sales made in "Midmarket".
- Number of Sales made in Goverment and Midmarket.
- Total Revenue generated from sales of "Montana" in Canada.
- The country, segment, Month that has the highest unit sold.
- Total profit made in December.



![Sales Png containing data](https://github.com/mjbrown-prog/First-Project/assets/64136357/f9bba6f6-9510-4270-aaba-59dc12b7b04e)

From the worksheet above, we would look into the following with formulars

- 1. To find the Total Revenue and Profit generated we use `=SUM(J2:J701,K2:K701)`
  2. To find average revenue and unit sold for every order we use `=AVERAGE(J2:J701,E2:E701)`
  3. To find the total discount given in $ we use `=SUM(I2:I701)`
  4. To find the Total Number of sales recorded. we use `=SUM(J2:J701)`
  5. To find the Highest Profit we use `=MAX(K2:K701)`
  6. To find the Average Revenue From Each Sale of "Paseo" we use `=AVERAGEIF(C2:C701, "Paseo", J2:J701)`
  7. To find the Number of Sales made in Goverment and Midmarket, we have to first of all find the number sales of Government and Number 
     of sales of Midmarket then add together ie using `=COUNTIF(A2:A701,"Government")`+ `=COUNTIF(A2:A701,"Midmarket")`. this would give
     desired answer.
  8. To find the Total Revenue generated from sales of "Montana" in Canada we use `=SUMIFS(J2:J701,M2:M701,"Canada",C2:C701,"Montana")`
  9. To find the The country, segment, Month that has the highest unit sold, we have to firstly find the "The highest unit og goods sold 
     which is `=MAX(E2:E701)` then you go ahead to the "Highest Unit of goods sold in Country" which is `=VLOOKUP(S20, E2:M701,9,FALSE)`, 
     then the "Highest Unit of goods sold in Segment" which is `=VLOOKUP(S20, E2:N701,10,FALSE)` and the "Highest unit of goods sold in 
      Months" which is `=VLOOKUP(S20,E2:L701,8,FALSE)`.
  10. To find the total profit made in December we use `=SUMIFS(K2:K701,L2:L701,"December")`.
 
Below is the answers generated with this formulas

![Sales Analysis](https://github.com/mjbrown-prog/First-Project/assets/64136357/1e25e13f-82a9-4532-b1b0-84309c55d228)

---

**IN CONCLUSION**

The skills i was able to demonstrate is Data Manupulation, Use of Conditional Formatting, Use of Filters, Text-to-column and use of some excel formulars.








