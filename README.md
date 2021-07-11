Description
Problem Statement

Suppose you are a backend developer who is tasked to create the Database schema for an ecommerce website. You are supposed to model the database which allows you to add customers, vendors, items and orders.

Tasks

You have to model four entities in tables: customers, vendors, items and orders

-- Customers: Every user is a customer. This should take name, username, password, etc.

-- Vendor: Vendor also needs to be registered as a customer first,  Then we make them vendor in vendor table. This table should hold the store name and other information of the vendor/store.

-- Items: Only registered vendors can add items in Items table across their vendor id(Foreign key from vendor table), this also takes quantity, unit price, etc.

-- Orders: This table is used to record orders by customers. This should capture customer_id, item_id(Foreign key from Items table), quantity, total amount etc.

-- You can create more tables for better design if you feel the need.

-- After creating schema, do a complete run from adding customers, making few vendors and adding their stores, adding items as those vendors/stores, place an order as a customer.

Deliverables

-- Database Dump with all the sample data of your SQLite3 database.

-- ERD diagram of your schema

-- Explanation.txt file, which explains your schema and design.