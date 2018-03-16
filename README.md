# Mongo Db

## See the exesting databases
```
show dbs
```
## Create a new Database
It will create a new database if not exist
```
use twitter
```
## Creating a new collection in thedb
```
db.createCollection('modi')
```
## Inerting the Data into the Collection
```
db.modi.insert({'bio':{'name': 'Narendra Modi','job':'Prime Minister'}})
```
## Checking the collections
```
show collections
```
## Querying the collection
```
db.modi.find()
```
## Inserting a new record
```
db.modi.insert({'bio':{'name': 'Rahul Gandhi','job':'Congress President'}})
```
Checking the Entire collection
```
db.modi.find()
```
## Inserting one more row into the modi collection
```
db.modi.insert({'name': 'Chandu','job':'AP CM'})
```
### Checking the collection
```
db.modi.find()
```
### Querying by name 
```
db.modi.find({'name':'Chandu'})
```
s
