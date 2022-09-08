# CMPG-323-Project-2---35383615

## Introduction

This project or rather repository consists of resources of a CRUD RESTful API created to manage IoT device data.The API will connect to a database storing all the relevant data of the IoT device.

## Functionality of the API

This Api allows users to manipulate data of the the IoT devices in various methods. Users can view the data,insert new data entries, update records as well as delete entries. There is security authentication implemented to ensure that no unauthorized users gain access to the information stored.

## EndPoints 

- GET methods as a EndPoints to access/view data, one can either view all data or specific data according to a specific ID entry on the various tables available.
  - a GET method that retrieves all Device entries from the database
  - a GET method that will retrieve one Device from the database based on the ID parsed through
  - a GET method that retrieves all Zone entries from the database
  - a GET method that will retrieve one Zone from the database based on the ID parsed through
  -  a GET method that retrieves all devices within a specific zone (based on the zone ID that is parsed through)
  -  a GET method that retrieves all Category entries from the database
  -  a GET method that will retrieve one Category from the database based on the ID parsed through
  -  a GET method that retrieves all devices within a specific category (based on the category ID that is parsed through)
  -  a GET method that will return the number of zones that are associated to a specific category (use the device entity to join the data)

- POST Methods as EndPoints to Create or Insert new entries into the relevant database table
- PATCH Methods as EndPoints to update existing entries on the picked table
- DELETE methods as EndPoints to remove specific records on the database

## Additional Aspects

The API is hosted on Web Cloud and there is Security (JWT Authentication) implemented on it.
