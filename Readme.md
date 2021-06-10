# Project 2: Data Modeling with Cassandra

In this project, we apply Data Modeling with Cassandra and build an ETL pipeline using Python. We will build a Data Model around our queries that we want to get answers for. For our use case we want below answers:

    Get details of a song that was herad on the music app history during a particular session.
    Get songs played by a user during particular session on music app.
    Get all users from the music app history who listened to a particular song.

# Datasets

For this project, you'll be working with one dataset: event_data. The directory of CSV files partitioned by date. Here are examples of filepaths to two files in the dataset:
event_data/2018-11-08-events.csv
event_data/2018-11-09-events.csv

# Project Steps

Below are steps you can follow to complete each component of this project:
Design tables to answer the queries outlined in the project template
Write Apache Cassandra CREATE KEYSPACE and SET KEYSPACE statements
Develop your CREATE statement for each of the tables to address each question
Load the data with INSERT statement for each of the tables
Include IF NOT EXISTS clauses in your CREATE statements to create tables only if the tables do not already exist. We recommend you also include DROP TABLE statement for each table, this way you can run drop and create tables whenever you want to reset your database and test your ETL pipeline
Test by running the proper select statements with the correct WHERE clause
