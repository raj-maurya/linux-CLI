# linux-CLI

- You can search for simple search strings
```{r, engine='bash', code_block_name} 
man -K "example text"
```
- Importing a Specific Database into MySQL
```{r, engine='bash', code_block_name} 
mysql --one-database database_name < all_databases.sql
```
- import a single table in to mysql database using command line
```{r, engine='bash', code_block_name} 
 mysql -u username -p databasename < path/example.sql
```
- Export a Specific Database from MySQL
```{r, engine='bash', code_block_name} 
 mysqldump database_name > database_name_dump.sql
```
- curl POST with a file
```{r, engine='bash', code_block_name} 
curl -X POST -F "image=@/path/example.gif" http://URL/uploadform.cgi
```
- curl POST to a form
```{r, engine='bash', code_block_name} 
curl -X POST -F "name=user" -F "password=test" http://URL/example.php
```


