# Music Store Data Analysis with PostgreSQL 🎵
This repository contains a comprehensive set of PostgreSQL queries designed to analyze a digital music store's database. The project serves as a practical demonstration of SQL skills, ranging from basic data retrieval to advanced analytical queries using Common Table Expressions (CTEs) and window functions to derive actionable business insights.

The SQL script, music_analysis_postgreSQL.sql, is structured as a series of questions and answers, exploring different facets of the business.

## Analysis Overview
The queries in this project are designed to answer key business questions, helping to understand customer behavior, sales trends, and genre popularity.

### Key Questions Addressed:
Employee Insights:

Identifying the most senior employee based on their job title.

Sales & Market Performance:

Determining which countries have the highest number of invoices.

Finding the top 3 highest invoice totals.

Identifying the city with the highest revenue, pinpointing a strategic location for a promotional music festival.

Customer Analysis:

Identifying the overall top-spending customer to recognize and reward loyalty.

Finding the top-spending customer within each country for targeted regional marketing.

Generating a mailing list (email, first name, last name) of all customers who listen to 'Rock' music.

Genre & Artist Popularity:

Compiling a list of the top 10 rock music artists by track count to invite to the promotional festival.

Calculating the total amount spent by each customer on the single best-selling artist.

Identifying the most popular music genre for each country based on the volume of purchases.

Track Data:

Returning a list of all track names that are longer than the average song length, ordered from longest to shortest.

## SQL Concepts Utilized
- This project demonstrates proficiency in a wide variety of SQL concepts, essential for data analysis:

- Data Retrieval & Filtering: SELECT, FROM, WHERE, LIKE

- Sorting & Limiting Results: ORDER BY, LIMIT

- Aggregation & Grouping: GROUP BY with aggregate functions like COUNT(), SUM(), and AVG().

- Joins: Using JOIN to combine data from multiple related tables (e.g., customer, invoice, track, artist, genre).

- Subqueries: Nesting queries in the WHERE clause to perform multi-step filtering and comparisons.

- Common Table Expressions (CTEs): Using the WITH clause to create temporary, readable result sets for breaking down complex analytical problems.

- Window Functions: Using ROW_NUMBER() with PARTITION BY to perform advanced ranking within specific categories, such as finding the top customer or genre within each country.
