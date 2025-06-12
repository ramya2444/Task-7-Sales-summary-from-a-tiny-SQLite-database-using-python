## Task 7 – Sales Summary using SQLite and Python

##  Objective
The goal of this task was to perform basic sales analysis using an SQLite database in Python. We queried the sales table to calculate:
- Total revenue per product
- Total quantity sold per product

We then visualized the results using bar charts with `matplotlib`.

---

##  Tools Used
- Python
- SQLite (via `sqlite3`)
- `pandas` – for data handling
- `matplotlib` – for plotting
- Jupyter Notebook

---

##  Files Included
- `sales_data.db` – SQLite database containing a sales table
- `sales_data script.ipynb` – Jupyter Notebook with all code and charts
- `sales_data script.pdf` - PDF version of the notebook (for easy offline or printable viewing)
- `sales_revenue by product.png` – Revenue bar chart
- `sales_quantity sold by product.png` – Quantity sold bar chart
- `README.md` – This documentation file

---

##  Chart Insights

###  Revenue by Product
- **Grapes** generated the highest revenue.
- **Apples** also performed well.
- **Bananas** earned the least revenue, possibly due to lower prices.

###  Quantity Sold by Product
- **Grapes** and **Apples** sold the highest number of units.
- **Oranges** and **Bananas** had relatively lower sales volume.

These charts provide a quick and clear understanding of product performance.

##  Conclusion

This task demonstrates the power of combining SQL with Python for quick, effective data analysis. 
Using just a few queries and visualization tools, we extracted meaningful insights from a simple dataset.This approach 
is scalable and can be applied to larger databases and more complex business problems in real-world data analysis workflows.
