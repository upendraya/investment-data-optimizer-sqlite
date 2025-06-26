# investment-data-optimizer-sqlite
A project to efficiently load, preview, and store large startup investment datasets using chunked reading in pandas and SQLite integration for lightweight querying and analysis.


1. Project Title & Tagline: investment-data-optimizer-sqlite
2. Dataset: Source: Crunchbase Startup Investments (via Kaggle)  
              File: investments_VC.csv  
3. Objectives:   Data Optimization: Choose the right data types and process large files in manageable chunks.
                 SQLite Integration: Store and query large datasets efficiently using SQLite.
                 Real-World Data Handling: Clean and prepare investment data for analysis.
                 Fundraising Trend Analysis: Uncover patterns in startup deals and investor activity.
                 Pandas-SQLite Workflow: Combine tools to analyze data at scale.
4.Steps Overview:  Detect encoding with `chardet`
                   Read and explore data in chunks
                   Clean each chunk (drop NaNs, filter rows)
                   Concatenate cleaned chunks
                   Save final dataset to SQLite
5.Dependencies:    pandas
                   chardet
                   sqlite3 (built-in)
   
