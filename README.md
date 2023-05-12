# CS-623project - Readme File 
This repository contains a Geographic Information System (GIS) database built using MongoDB. The database is named "GIS" and includes a collection called "geodata". This readme file provides an overview of the database structure and instructions on how to use various functionalities.

Create the GIS Database: Open a MongoDB client (such as MongoDB Shell) and create a new database named "GIS"

Create the geodata Collection: To create the "geodata" collection within the "GIS" database,

Insert locations into the geodata collection, use the insertOne() or insertMany() methods provided by MongoDB

To calculate the distance between two points, you can use the $geoNear aggregation pipeline stage in MongoDB. 

Find all locations within a certain area, you can use a geospatial query such as $geoWithin 

We can use the explain() method to get query execution details, including the query plan, execution time, and index usage.

To sort query results in ascending or descending order, you can use the sort() method

We can limit the number of results returned using the limit() method.

To optimize query performance, consider Indexing techniques

Thank you!
