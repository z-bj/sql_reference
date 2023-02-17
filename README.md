#SQL Reference

``` json
{
    "database": {
        "create": "CREATE DATABASE database_name;",
        "drop": "DROP DATABASE database_name;",
        "rename": "ALTER DATABASE database_name RENAME TO new_name;"
    },
    "table": {
        "create": "CREATE TABLE table_name();",
        "drop": "DROP TABLE table_name;",
        "rename": "ALTER TABLE table_name RENAME TO new_name;"
    },
    "row": {
        "insert": "INSERT INTO table_name(columns) VALUES(values);",
        "update": "UPDATE table_name SET column_name = new_value WHERE condition;",
        "delete": "DELETE FROM table_name WHERE condition;"
    },
    "column": {
        "add": "ALTER TABLE table_name ADD COLUMN column_name;",
        "drop": "ALTER TABLE table_name DROP COLUMN column_name;",
        "rename": "ALTER TABLE table_name RENAME COLUMN column_name TO new_name;",
        "primary_key": "ALTER TABLE table_name ADD PRIMARY KEY(column_name);",
        "foreign_key": "ALTER TABLE table_name ADD FOREIGN KEY(column_name) REFERENCES table_name(column_name);"
    }
}

```
