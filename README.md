### Scenario 1: Find Top-Selling Product in Each Region  
You are given two tables:  
1. Sales Data [SaleID, Region, Product, Amount]  
2. Product Details [Product, Category, Price]  

**Task**: Find the top-selling product (based on Amount) in each region, along with its Category.  

---

### Scenario 2: Customer Retention Analysis  
You are given a table: [CustomerID, Name, Country]  

**Task**: Identify customers who haven't made a transaction in the past 6 months.  

---

### Scenario 3: Year-over-Year Sales Growth  
You have the following table: Sales Table [Year, Month, Region, Sales]  

**Task**: Calculate the percentage growth in sales for each region from 2022 to 2023.  

---

### Scenario 4: Order Value Segmentation  
You are given two tables:  
1. Orders [OrderID, CustomerID, OrderValue]  
2. Customers [CustomerID, Name, Segment]  

**Task**: Categorize customers into different segments (e.g., High Value, Medium Value, Low Value) based on their total order value.  

---

### Scenario 5: Find Common Customers Between Two Platforms  
You are given two tables:  
1. Platform A Customers [CustomerID, Name, Email]  
2. Platform B Customers [CustomerID, Name, Email]  

**Task**: Identify customers who exist in both platforms.  

---

### Scenario 6: Calculate Active Users by Region  
You are given two tables:  
1. Users [UserID, Region, LastLoginDate]  
2. Transactions [TransactionID, UserID, Date]  

**Task**: Calculate the number of active users (who made a transaction in the last 30 days) for each region.  

---

### Scenario 7: Generate a Product Pair Recommendation  
You are given a table: [OrderID, Product]  

**Task**: Identify all product pairs frequently bought together in the same order.  

---

### Scenario 8: Calculate Cumulative Sales  
You are given a table: [Date, Region, Sales]  

**Task**: Calculate the cumulative sales for each region over time.  

---

### Scenario 9: Identify Products with No Sales  
You are given two tables:  
1. Products [ProductID, ProductName]  
2. Sales [SaleID, ProductID, Amount]  

**Task**: Find all products that have no sales.  

---

### Scenario 10: Identify the Highest Spending Customer  
You are given two tables:  
1. Customers [CustomerID, Name, Country]  
2. Transactions [TransactionID, CustomerID, Amount]  

**Task**: Identify the customer who has spent the most, along with the total amount spent.  
### Scenario 11: Explode and Map Data Across Columns  
You are given a DataFrame with two columns:  
1. `col_a` contains names separated by commas (e.g., "ram,shyam").  
2. `col_b` contains countries separated by commas (e.g., "USA,Canada").  

**Task**: Explode both columns such that each name from `col_a` is mapped to the corresponding country from `col_b`.  

Example:  
Input:  
col_a: "ram,shyam", col_b: "USA,Canada"  
col_a: "puja,rohit", col_b: "UK,India"  

Output:  
ram → USA, shyam → Canada, puja → UK, rohit → India  

---

### Scenario 12: Nested JSON Handling  
You are given a table:  
1. Data [ID, Details]  
   - The `Details` column contains JSON strings (e.g., {"name": "Alice", "age": 25}).  

**Task**: Parse the `Details` column to extract two new columns: `Name` and `Age`.  

---

### Scenario 13: Pivot and Unpivot Data  
You are given a table:  
1. Data [ID, Metric, Value]  
   - The `Metric` column contains labels like "Sales" or "Profit".  
   - The `Value` column contains corresponding numerical values.  

**Task**:  
1. Pivot the table to make `Metric` values (like "Sales" and "Profit") as columns.  
2. Unpivot the table back to its original form.  

---

### Scenario 14: Handle Skewed Data  
You are given a table:  
1. Sales Data [Region, Sales]  
   - The `Region` column contains data with a highly skewed key (e.g., "North" appears in most rows).  

**Task**: Distribute the data more evenly by splitting the skewed key (e.g., "North") into sub-keys like "North_1", "North_2".  

---

### Scenario 15: Rolling Window Calculation  
You are given a table:  
1. Sales Data [Date, Product, Sales]  

**Task**: Calculate the rolling 2-day sum of `Sales` for each product.  

---

### Scenario 16: Data Deduplication  
You are given a table:  
1. Employee Data [EmpID, Name, Department, Updated_At]  

**Task**: Remove duplicates but keep only the latest record for each `EmpID` based on the `Updated_At` timestamp.  

---

### Scenario 17: Mismatched Column Names  
You are given two tables with mismatched column names:  
1. Employees A [EmpID, Name, Dept]  
2. Employees B [EmployeeID, FullName, Department]  

**Task**: Perform a join between these two tables by mapping mismatched column names (`EmpID` to `EmployeeID`, `Name` to `FullName`, etc.).  

---

### Scenario 18: Combine and Rank Data  
You are given two tables:  
1. Scores [StudentID, Subject, Score]  
2. Students [StudentID, Name]  

**Task**: Combine the data and rank students within each subject by their scores.  

---

### Scenario 19: Flattening Nested Arrays  
You are given a table:  
1. Data [Col_A]  
   - The `Col_A` column contains nested arrays (e.g., [1, 2, 3]).  

**Task**: Flatten the nested arrays into separate rows.  

---

### Scenario 20: Compare Sales Performance  
You are given two tables:  
1. Sales_2022 [Region, Product, Sales]  
2. Sales_2023 [Region, Product, Sales]  

**Task**: Compare the sales performance of each product across the two years and identify products with a significant increase or decrease in sales.  
