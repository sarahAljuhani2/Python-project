# 🐍 Python Project: Sales Transaction Analysis

## 📝 About the Data

This dataset contains **sales transaction data** from a **UK-based e-commerce store** operating in London. The store has been selling gifts and homewares for adults and children online since 2007. Customers include individuals and small businesses worldwide.

The dataset includes:
- **500,000 rows**
- **8 columns**
- Covers **one full year** of transactions

---

##  Column Descriptions

1. **TransactionNo** *(Categorical)*:  
   A six-digit unique ID for each transaction.  
   > Note: Codes with the letter “C” represent cancellations.

2. **Date** *(Numeric)*:  
   The date on which the transaction occurred.

3. **ProductNo** *(Categorical)*:  
   Unique identifier (5 or 6 digits) for each product.

4. **Product** *(Categorical)*:  
   Name or description of the product/item.

5. **Price** *(Numeric)*:  
   Unit price in pound sterling (£).

6. **Quantity** *(Numeric)*:  
   Number of units purchased per transaction.  
   > Negative values indicate cancelled transactions.

7. **CustomerNo** *(Categorical)*:  
   A five-digit unique number identifying the customer.

8. **Country** *(Categorical)*:  
   Country where the customer resides.

---

##  Cancellations

There is a **small percentage** of order cancellations in the dataset.  
Most cancellations are due to **out-of-stock** items, where customers prefer to cancel entire orders if any part is unavailable.

---

