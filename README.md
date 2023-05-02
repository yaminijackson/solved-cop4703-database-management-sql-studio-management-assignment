Download Link: https://assignmentchef.com/product/solved-cop4703-database-management-sql-studio-management-assignment
<br>
COP4703 Database Management

SQL Studio Management Assignment.

USE ClearWater;

Query 1. (10 points)

Display ProductID, ProductName, and UnitPrice of products if the 3rd letter from the end of their ProductName is ‘a’ and have a unit price of $25 or higher. Solve this query by writing a SELECT statement with the LIKE operator.

Query 2. (10 points)

Solve Query 1 by writing another SELECT statement that uses LEFT() and RIGHT() functions without LIKE.

Hint: A function’s output could become an input of the other such asLEFT(RIGHT(…, …), …) or RIGHT(LEFT(…, …), …).

Query 3.

Find suppliers whose phone number contains exactly two ‘5’s, no more and no less. Display their SupplierID and Phone. The output must be sorted by phone number in the Z -&gt; A order.

Query 4.

Find products that satisfy the two conditions described below:

(a) Unit price must NOT higher than $10.

(b) Its category ID is 3 or 6 or 7 or 8. Otherwise, if its category is 1 or 5, it must have more than at least 40 units in stock. Display their ProductID, UnitPrice, CategoryID, and UnitsInStock. The output should be sorted by CategoryID in A -&gt; Z order. For those with the same CategoryID, the one with the highest UnitPrice should be  displayed first.

Query 5.

Among products that meet both (a) and (b) conditions specified in Query 4, if we rank them in Z -&gt; A order of ProductID, the one with the largest ProductID will be ranked as #1. Based on the rank, find only three of them which are ranked #5, #6, and #7. The output should contains same four columns as in Query 4.


