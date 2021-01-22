# cassandra_sparkify_db
Code base goes through a few basic tasks.  
First is a simple ETL pipeline, where we crawl a directory of CSV files, and then parse the necessary information, and concatenate those together while written a new CSV file.  
Next, we use that saved CSV file, to populate our casandra DB that we will use to answer a few questions about our data.  We design tables that allow us to answer our questions, populate those, and then run queries to ensure the necessary information is returned.