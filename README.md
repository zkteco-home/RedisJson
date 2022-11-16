# RedisJson

RedisJSON is a Redis module that implements ECMA-404 The JSON Data Interchange Standard as a native data type. 
It allows storing, updating and fetching JSON values from Redis keys (documents).

Compliled on https://github.com/RedisJSON/RedisJSON 

# Primary features:

Full support of the JSON standard

JSONPath syntax for selecting elements inside documents

Documents are stored as binary data in a tree structure, allowing fast access to sub-elements

Typed atomic operations for all JSON values types

# Run

## Solution 1:
  add parameters to redis.conf
  
  enable-module-command yes
  
  loadmodule rejson.dll
## Solution 2:

  redis-server.exe --loadmodule rejson.dll
  
  
