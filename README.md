# Inventory_Management_System
The Grocery Inventory Management System is an end-to-end database project designed to streamline the restocking process for small to mid-size supermarkets. The system manages both warehouse and in-store restocking, improving labor productivity and sales efficiency. 

# Data Source: The schema was created from scratch and populated with randomly generated data using Mockaroo, a data generation tool.


# Key Steps:
# Conceptual Data Modeling:
EER Diagram: Developed an Enhanced Entity-Relationship diagram to represent the database schema.
UML Diagram: Created a Unified Modeling Language diagram to illustrate system components and their interactions.

# Mapping Conceptual Model to Relational Model:
Designed relational models ensuring primary and foreign key constraints to maintain data integrity.
Normalized the database up to BCNF to eliminate redundancies and anomalies.

# Database Implementation:
# MySQL Implementation:
Created the database schema using Data Definition Language (DDL) statements.
Imported data and used Data Manipulation Language (DML) for querying and obtaining necessary results.
Key Queries:
Truck schedule information retrieval
Product balance checks
Order details and employee information extraction
# NoSQL Implementation (MongoDB):
Executed MongoDB queries for specific data retrieval needs, such as finding products with low balance on hand and calculating total costs.

# Database Access via Python:
Connected the MySQL database to Python using mysql.connector.
Used Pandas for data manipulation and Matplotlib/Seaborn for data visualization.

# Visualizations:
Bar plots for order fulfillment time distribution
Histograms for employee age distribution
Pie charts for product balance comparisons

# System Features:
Automated order placement based on inventory levels
Employee login and shift schedule tracking
Real-time tracking of truck schedules and product deliveries
Aisle mapping for efficient shelf restocking
Comprehensive tracking of product stock and balance

# Conclusion:
The system significantly improved labor productivity and reduced overtime expenses by providing employees with detailed insights into their schedules and inventory needs.
The integration of stock and reserve views helped stores prioritize best-selling items, enhancing overall sales efficiency.
Future improvements include incorporating labor standards, stocking time optimization, and implementing machine learning models for further efficiency gains.

# Tech Stack:
Programming Languages: Python, SQL
Database Management Systems: MySQL (SQL-based), MongoDB (NoSQL-based)
Libraries: Pandas (for data manipulation), Matplotlib and Seaborn (for data visualization)
Tools: Jupyter Notebook (for development and analysis), MySQL Workbench (for database management), MongoDB Compass (for NoSQL database management)
