# Book Store 
This is my repo for book store project
- used gorilla/mux
- postgresql 

POST 
- ```curl.exe -X POST http://localhost:8080/books/ -H "Content-Type: application/json" -d '{\"author\":\"tulen\", \"name\":\"alximik\",\"price\":1000, \"sellerid\":2}'```
- ```curl.exe -X POST http://localhost:8080/books/ -H "Content-Type: application/json" -d '{\"author\":\"aliau\", \"name\":\"1984\",\"price\":100, \"sellerid\":2}'```

PUT
- ```curl.exe -X PUT http://localhost:8080/books/statusu/1 -H "Content-Type: application/json"```
- ```curl.exe -X PUT http://localhost:8080/books/priceid/1/ -H "Content-Type: application/json" -d '{\"price\":5000}'```

DELETE
- ```curl.exe -X DELETE http://localhost:8080/books/delete/2/ -H "Content-Type: application/json"```

GET 
- озын карап ал😁

USER истеуге ерынып калдым, может сосын истеймын👨‍🍳