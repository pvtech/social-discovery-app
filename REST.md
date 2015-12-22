#Restful End Points

All endpoints to be used are to be defined in the format - (apiaryblueprint)[https://github.com/apiaryio/api-blueprint#readme]

# GET /users
 - ``` Response 200 ```
 - ``` application/json ```
 - List of all users paginated
 - Returns ``` [ {user} ] ``` 
 
# POST /users
 - ``` Response 201 ```
 - ``` application/json ```
 - Input Body - user schema 
 - ID of the current user created by the system
