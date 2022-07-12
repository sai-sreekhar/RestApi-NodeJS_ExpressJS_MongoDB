1. To Create Databases:

    --> use <database-name>.
    The newly created database will NOT be visible unless we insert any document inside it.
    Make sure we see the message switched to db <database-name>.

2. List all databases in MongoDB --> show databases

3. Shows the database we are currently workign in --> db

4. To Drop Database:

    First we need to select the database.
    --> use <database-name>
    --> db.dropDatabase()

5. To Create Collection --> db.createCollection("<name of collection>")

6. To Drop a Collection --> db.<collection name>.drop() (here db is current working database)

