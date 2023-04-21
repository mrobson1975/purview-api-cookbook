# purview-api-cookbook
A collection of notebooks and scripts to augment Microsoft Purview functionality leveraging REST APIs.  These examples use native REST capabilities in order to aid understanding of the Apache ATLAS payloads.  Other resources, such as Will Johnson's great [pyapacheatlas](https://github.com/wjohnson/pyapacheatlas) offer more succinct code patterns with lots of additional examples.

## Index of scripts

| Folder | Script | Description |
| ------ | ------ | ----------- |
| config | config.yaml | Configuration file containing Purview environment and Service Principal details.
| lineage | lineage-tutorial.ipynb | Step-by-step walkthrough covering the creation of basic entities and column-level lineage
| entity | entity-create-simple.ipynb | Simple example of creating an Azure SQL server, db, schema, table and columns
| entity | entity-bulk-delete-from-collection.ipynb | Example of bulk deleting all entities in a collection