#Top used database management systems

![Alt text](./images/topdb.png?raw=true)

https://enlyft.com/tech/database-management-system
```
Database               Global Usage      Market Share
Microsoft SQL Server   166,889 	          21%
MySQL 	               160,051	          20%
Microsoft Access       85,854	          11%
PostgreSQL             44,669	         < 5%
MongoDB                38,237	         < 5%
...
Apache Cassandra       4,686             < 5% 

```
https://enlyft.com/tech/products/apache-cassandra
# RDBMS
* RDBMS stands for Relational Database Management System.

* SQL stands for Structured Query Language
* SQL lets you access and manipulate database
* SQL became a standard of the American National Standards Institute (ANSI) in 1986, and of the International Organization for Standardization (ISO) in 1987
* Although SQL is an ANSI/ISO standard, there are different versions of the SQL language.
* However, to be compliant with the ANSI standard, they all support at least the major commands (such as SELECT, UPDATE, DELETE, INSERT, WHERE) in a similar manner.
## Microsoft SQL Server 
![Alt text](./images/MicrosoftSQLServer.png?raw=true)
This database management engine works on cloud-based servers as well as local servers, and it can be set up to work on both at the same time. 
Not long after the release of Microsoft SQL Server 2016, Microsoft made it available on Linux as well as Windows-based platforms.

Some of the standout features for the 2016 edition include temporal data support, which makes it possible to track changes made to data over time. 

The latest version of Microsoft SQL Server also allows for dynamic data masking, which ensures that only authorized individuals will see sensitive data.

__Pros__

* It is very fast and stable.
* The engine offers the ability to adjust and track performance levels, which can reduce resource use.
* You are able to access visualizations on mobile devices.
* It works very well with other Microsoft products.

__Cons__

* Enterprise pricing may be beyond what many organizations can afford.
* Even with performance tuning, Microsoft SQL Server can gobble resources.
* Many individuals have issues using the SQL Server Integration Services to import files.


Ideal for: Large organizations that use a number of Microsoft products.

## MySQL
![Alt text](./images/MySQL.png?raw=true)
MySQL is one of the most popular databases for web-based applications. It’s freeware, but it is frequently updated with features and security improvements. There are also a variety of paid editions designed for commercial use. With the freeware version, there’s a greater focus on speed and reliability instead of including a vast array of features, which can be good or bad depending on what you’re attempting to do.

This database engine allows you to select from a variety of storage engines that enable you to change the functionality of the tool and handle data from different table types. It also has an easy to use interface, and batch commands let you process enormous amounts of data. The system is also incredibly reliable and doesn’t tend to hog resources.

__Pros__

* It’s available for free.
* It offers a lot of functionality even for a free database engine.
* There are a variety of user interfaces that can be implemented.
* It can be made to work with other databases, including DB2 and Oracle.

__Cons__

* You may spend a lot of time and effort to get MySQL to do things that other systems do automatically, like create incremental backups.
* There is no built-in support for XML or OLAP.
* Support is available for the free version, but you’ll need to pay for it.

Ideal for: Organizations that need a robust database management tool but are on a budget.

## PostgreSQL

PostgreSQL is one of several free popular databases, and it is frequently used for web databases. It was one of the first database management systems to be developed, and it allows users to manage both structured and unstructured data. It can also be used on most major platforms, including Linux-based ones, and it’s fairly simple to import information from other database types using the tool.

This database management engine can be hosted in a number of environments, including virtual, physical and cloud-based environments. The latest version, PostgreSQL 9.5, offers larger data volumes and an increase in the number of concurrent users. Security has also been improved thanks to support for both DBMS_SESSION and expanded password profiles.

__Pros__

* This database management engine is scalable and can handle terabytes of data.
* It supports JSON.
* There are a variety of predefined functions.
* A number of interfaces are available.

__Cons__

* Documentation can be spotty, so you may find yourself searching online in an effort to figure out how to do something.
* Configuration can be confusing.
* Speed may suffer during large bulk operations or read queries.

Ideal for: Organizations with a limited budget that want the ability to select their interface and use JSON.

#NoSQL DB
Developed in late 2000s to deal with limitations of SQL databases, especially scalability, multi-structured data, geo-distribution and agile development sprints
NoSQL Database Types
Document databases pair each key with a complex data structure known as a document. Documents can contain many different key-value pairs, or key-array pairs, or even nested documents.

Graph stores are used to store information about networks of data, such as social connections. Graph stores include Neo4J and Giraph.

Key-value stores are the simplest NoSQL databases. Every single item in the database is stored as an attribute name (or 'key'), together with its value. Examples of key-value stores are Riak and Berkeley DB. Some key-value stores, such as Redis, allow each value to have a type, such as 'integer', which adds functionality.

Wide-column stores such as Cassandra and HBase are optimized for queries over large datasets, and store columns of data together, instead of rows

More to read: https://www.mongodb.com/nosql-explained

## MongoDB

Another free database that also has a commercial version, MongoDB is designed for applications that use both structured and unstructured data. The database engine is very versatile, and it works by connecting databases to applications via MongoDB database drivers. There is a comprehensive selection of drivers available, so it’s easy to find a driver that will work with the programming language being used.

Since MongoDB wasn’t designed to handle relational data models, even though it can, performance issues are likely to crop up if you attempt to use it this way. However, the database engine is designed to handle variable data that isn’t relational, and it can often work well where other database engines struggle or fail.

MongoDB 3.2 is the latest version, and it features new pluggable storage engines. Documents can also now be validated during updates and inserts, and the text search functions have been improved. A new partial index capability also may allow for improved performance by shrinking the size of indexes.

Pros

* It’s fast and easy to use.
* The engine supports JSON and other NoSQL documents.
* Data of any structure can be stored and accessed quickly and easily.
* Schema can be written without downtime.

Cons

* SQL is not used as a query language.
* Tools to translate SQL to MongoDB queries are available, but they add an extra step to using the engine.
* Setup can be a lengthy process.
* Default settings are not secure.


## Hadoop, Spark, Cassandra
Apache Cassandra is one of the most popular NoSQL databases. It offers great performance and scalability without sacrificing availability. It has no Single Point of Failure (SPOF). The biggest, publicly announced cluster contains over 115k nodes and over 10PB of data. However, Cassandra data format differs from what you got used to in the SQL world. There are tables with special keys but without relations. What is the most important, it is not possible to query data using any arbitrary column. Cassandra is not perfect for every project, there are many mistakes which can be made when working with it. 
https://dzone.com/articles/hadoop-vs-spark-a-head-to-head-comparison
https://www.scnsoft.com/blog/cassandra-vs-hadoop

# TimeSeries DB
A time series database (TSDB) is a database optimized for time-stamped or time series data. Time series data are simply measurements or events that are tracked, monitored, downsampled, and aggregated over time. This could be server metrics, application performance monitoring, network data, sensor data, events, clicks, trades in a market, and many other types of analytics data.

A time series database is built specifically for handling metrics and events or measurements that are time-stamped. A TSDB is optimized for measuring change over time. Properties that make time series data very different than other data workloads are data lifecycle management, summarization, and large range scans of many records.

![Alt text](./images/timeseriesdata.png?raw=true)
![Alt text](./images/timeseriesdb.png?raw=true)