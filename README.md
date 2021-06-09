# JWT-implementaion
Jwt implementation using microservices
Test it using below call in postman.

1. POST http://localhost:8081/auth/authenticate
{
    "username":"admin",
    "password":"password"
}

2. GET http://localhost:8081/auth/api/secure

use token from previous call and hit the above and get the result.
