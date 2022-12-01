### dependencies
```
$npm i wikiapi
$npm i express
$npm i helmet
```
### Setup Startup
package.json
```
  "script": {
    "start": "node server.js"
  },

$npm start
```
### SCHEMA
```
CREATE DATABASE wiki_api;
CREATE TABLE wiki_user(id SERIAL PRIMARY KEY, user_name VARCHAR(20), user_password CHAR(60), last_update DATE NOT NULL DEFAULT CURRENT_DATE);
```
### REQUEST FORMAT
```
http://localhost:9999/AccountAuth
username
password

```