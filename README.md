# sonq

__sonq__ means son query, is tool for son like objects, for example, json and bson. You may use sonq to query .bsonor newline separated .json files directly from command line.


## Install

```
pip install sonq
```

## Basic Usage

- List the content of a .bson file
```
sonq source.bson
```
- Query a .bson file
```
sonq -f '{"name": "Stark"}' source.bson
```
- Convert query results to a newline separated .json file
```
sonq -f '{"name": "Stark"}' -o target.json source.bson
```