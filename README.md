# Sandman Auto-Generated API

This project demonstrates the use of **Sandman2** to auto-generate a RESTful API from an SQLite database.

## Tool Used
- **Sandman2**: Automatically generates an API based on an existing database.

## Steps to Set Up
1. Created an SQLite database `my_database.db` with a sample table (`products`) and inserted sample data.
2. Installed Sandman2 using `pip install sandman2`.
3. Ran Sandman2 with the SQLite database to auto-generate the API:
   ```bash
   sandman2ctl sqlite:///path/to/my_database.db
