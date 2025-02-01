# SQL-projects
The collection of the SQL Projects.
Project 1: Online Bookstore Database
This project contains a SQL script to manage an online bookstore database.

Features:
Database and Tables: Creates OnlineBookstore database with tables Books, Customers, and Orders.
Data Import: Imports data from CSV files into the tables.
Queries: Includes basic and advanced SQL queries for data retrieval and analysis, such as:
Retrieving books by genre
Listing customers by country
Calculating total stock and revenue
Usage:
Create Database:

SQL
CREATE DATABASE OnlineBookstore;
\c OnlineBookstore;
Create Tables and Import Data:

SQL
-- Define tables and import data from CSV files
Execute Queries:

SQL
SELECT * FROM Books WHERE Genre='Fiction';
-- Additional queries included in the script
