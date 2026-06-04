# preface

This project is about migrating enterprise data from SQL server into postgres.

we'll be using

- SQL
- python
- Jupyter notebook

# pseudocode

## High-level

1. Audit the data in SQL(before migration)
2. Extract data from SQL server(SSMS)
3. Transform the data
4. Load the data in postgreSQL
5. Validate the data (after migration)
6. Generate a validation report

## Low-level

- Create a .env file
- Load env variables
- Connect to SQL server (pyodbc)
- connect to Postgres (psycopg2)
- Audit the data
  - For Each table
  - Get row count
  - Extract all table rows
