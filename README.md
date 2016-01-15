# basic go API example

build and run the API and it will be served at: http://localhost:8080/

use the following curl command to test it out:
```
curl -H "Content-Type: application/json" -d '{"name":"New Todo"}' http://localhost:8080/todos
```

Tutorial followed here: http://thenewstack.io/make-a-restful-json-api-go/
