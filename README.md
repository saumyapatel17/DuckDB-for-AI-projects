What is DuckDB?
DuckDB is a modern, high-performance, in-memory analytical database management system (DBMS) designed to support complex analytical queries. It is a relational (table-oriented) DBMS that supports the Structured Query Language (SQL). 

DuckDB combines the simplicity and ease of use of SQLite with the high-performance capabilities required for analytical workloads, making it an excellent choice for data scientists and analysts.


### Key Features of DuckDB:
1. **In-Process Execution**: DuckDB runs in the same process as your application, eliminating the need for a separate database server.
   
2. **Columnar Storage**: It uses a columnar storage format, which is ideal for analytical queries, as it allows for efficient compression and retrieval of specific columns.

3. **Optimized for Analytics**: DuckDB is built to handle complex analytical queries involving aggregations, joins, and window functions efficiently.

4. **SQL Compatibility**: It supports standard SQL queries, making it easy for developers and analysts to work with.

5. **Lightweight and Portable**: DuckDB doesn't require any setup or maintenance, and its database files are portable across systems.

6. **Integration with Popular Tools**: It integrates seamlessly with Python (via the `duckdb` Python package), R, and other languages and frameworks, making it useful in data science and ETL pipelines.

7. **Performance**: DuckDB can process large datasets efficiently, often matching or exceeding the performance of more complex systems for analytical tasks.

8. **Free and Open Source**: DuckDB is released under the permissive MIT license, making it a popular choice for a wide range of projects.

### Common Use Cases:
- **Exploratory Data Analysis (EDA)**: Quickly analyzing large datasets without needing to set up a dedicated database server.
- **ETL Pipelines**: As part of Extract-Transform-Load workflows, DuckDB can process data in memory or read/write from/to formats like Parquet, CSV, and others.
- **Embedded Analytics**: Applications that need in-process analytics capabilities can embed DuckDB directly.

We will load a CSV file and create a "bank" table. The dataset we are using is available on DataLab and is called Bank Marketing. It consists of direct marketing campaigns by a Portuguese banking institution using phone calls.

https://www.datacamp.com/tutorial/building-ai-projects-with-duckdb