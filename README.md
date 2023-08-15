# **Backend User System** 

- Purpose of this project is to build a backend using Spring boot, which allows users to register, email verification link and login.

## Postman

- Using postman we can hit the following endpoints to Post and Get, to the app.

**Post:** localhost:8080/api/v1/registration
**body:** {
    "firstName": "John",
    "lastName": "Doe",
    "email": "john@gmail.com",
    "password": "password"
}

- Allows us to add users to the database

**Get:** localhost:8080/api/v1/registration/confirm?token=4493165b-3885-42ae-b188-e79622dd6b6b
**body:** {
    "firstName": "John",
    "lastName": "Doe",
    "email": "john@gmail.com",
    "password": "password"
}

- After email is confirmed, we will get a token.


## Maildev

- MailDev is a simple way to test your project's generated email during development, with an easy to use web interface that runs on your machine built on top of Node.js (https://github.com/maildev/maildev).

- To run maildev simply type `maildev` to your terminal.  
