# srijan-wolfram-api-wrapper

This project is a wrapper which uses the wolfram alpha api to search content.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

download this project and go to the project directory.

1. Node.js package should be installed in system

do - 
```
npm install
```

### Installing

A step by step series of examples that tell you have to get a development env running


```
1. npm install
```
```
2. tsd install
```
```
3. tsd link
```
```
4. gulp
```
Once run the gulp make sure there is not any compilation error during the gulp.

## Running the tests

node dist\bin\www.js

once you run the above command in terminal you will see a message on a console ---- Listening on port 9215 ----

first go to this url and create a user after sucess you will get a token for future request.

http://localhost:9215/signup 

you will have to give the userName & passoword then you will receive a token you need this token 
for subsequent request.

### token will be only valid for 1 hour after one hour you will have to again sign up and get the token.


After getting the token Now you can send the query to server to be searched for wolfram alpha api.

Send the request in this fashion url --- 
--------------------------------------------------------------
http://localhost:9215/search/how far is sun from earth
http://localhost:9215/search/integrate x^2
--------------------------------------------------------------


### After getting token , while sending the request to server send the token in request via http header
### Set the header's key - "authorization" and header's value to signup token.


Let me know of any Issue while using it.



