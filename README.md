# Document Search Using MongoDb

## Description:
* This is command line application using Node.js.
* This project search user entered terms in the database and
  returns the total count and 1st encountered line to the console


## Pre-requisite:
  MongoDb, Node.

## Running commands:
```bash
node index.js DB_URL COMMAND [COMMAND_ARGS...] 
```

where COMMAND is:

        add-content CONTENT-FILE...
        add-noise NOISE-FILE...
        clear
        complete SEARCH-TERM...
        find SEARCH-TERM...
        get DOC_NAME

e.g.
```bash
node index.js mongodb://localhost:27017/docs find betty
```