# Worldwide-importers-DB

In this repository, we will use this fictitious database of Worldwide importers to practice SQL problems.

worldwide importers sample database information-
https://learn.microsoft.com/en-us/sql/samples/wide-world-importers-what-is?view=sql-server-ver16

Data dictionary link
https://dataedo.com/samples/html/WideWorldImporters/doc/WideWorldImporters_5/home.html

**Workflow of the business**

1. WWI creates purchase orders and submits the orders to the suppliers.

2. Suppliers send the items, WWI receives them and stocks them in their warehouse.

3. Customers order items from WWI

4. WWI fills the customer order with stock items in the warehouse, and when they don't have sufficient stock, they order the additional stock from the suppliers.

5. Some customers don't want to wait for items that aren't in stock. If they order say five different stock items, and four are available, they want to receive the four items and backorder the remaining item. The item would then be sent later in a separate shipment.


6. WWI invoices customers for the stock items, typically by converting the order to an invoice.

7. Customers might order items that aren't in stock. These items are backordered.

8. WWI delivers stock items to customers either via their own delivery vans, or via other couriers or freight methods.

9. Customers pay invoices to WWI.

10. Periodically, WWI pays suppliers for items that were on purchase orders. This is often sometime after they've received the goods.

**Steps to use repository for your practice**
1. Create 6 customized tables in your worldwideimporters database. These tables are Dbo.Orders, Dbo.OrderLines, Dbo.Customers, Dbo.Invoices, Dbo.InvoiceLines and Dbo.StockItems.
2. Code to create tables is present in file named '1_create_your_custom_tables'
3. Description of fields present in custom details are available in the file named '2_Column_description_for_the_custom_tables'
4. Start with beginner problems present in file- 10 SQL problems for beginners
   

