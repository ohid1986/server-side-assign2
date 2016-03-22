# server-side-assign2

Assignment Overview

In this assignment, you will continue your journey with MongoDB and Mongoose. You will update the Dishes schema and model to support a few new fields in the schema. You will then create two new schemas for promotions and leadership, and test them by implementing a simple server. At the end of this assignment you would have completed the following three tasks:

Updated the Dishes schema and model to support some new fields and tested with a modified server.
Implemented the Promotions schema and model, and tested with a new server
Implemented the Leaders schema and model, and tested with a new server.

Task 1

The updated Dishes schema and model is correctly updated to support the new fields: image, category, label and price.
The label field is set to an empty string by default
The price schema is be supported with a new SchemaType called Currency.

Task 2

The Promotions schema and model correctly supports all the fields as per the example document given 
The label field is set to an empty string by default
The price schema is be supported with a new SchemaType called Currency.

Task 3

The Leaders schema and model correctly supports all the fields as per the example document given.

Folders

mongodb - mongodb database

How to use

1. Git clone to your computer
2. Run mongod database using 'mongod --dbpath drive_name:\server-side\mongodb\data --storageEngine=mmapv1' command if wiredTiger not supported
$ cd/server-side-assign2
$ cd/node-mongoose
$ npm install
$ node dishServer
$ node promoServer
$ node leaderServer
