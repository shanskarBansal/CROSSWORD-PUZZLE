<h1 align="center">
    <b>CrossWord Puzzle Game<br> Node.js using MongoDB </b> 
<br>
</h1>

## What is this for?

A crossword is a word puzzle that usually takes the form of a square or a rectangular grid of white- and black-shaded squares. The goal is to fill the white squares with letters, forming words or phrases that cross each other, by solving clues which lead to the answers.

### •Registration Form:

Allows the user to register their account by filling their Email, Username, Password.

### •Login Form:

If the user has been registered on the app, can login by passing the credentials.

### DataBase:

Here we use **[MongoDB Atlas(Cloud)](https://www.mongodb.com/cloud/atlas)** as the database. Here we have two collection created, named as:

- users.
- sessions.

A Collection(**Users**) is populated with the user's credentials.

A Collection(**session**) is created which stores the users Logged session.

## Prerequisites

Tools that we need to run this app:

- **_[Node.js](https://nodejs.org/en/)_**
- **_[Node Package Manager](https://www.npmjs.com/get-npm)_**
- **_[MongoDB (Atlas)](https://www.mongodb.com/cloud/atlas)_**

## Installing

```
npm install
```

## Connection to DataBase Access

At line 11 on `./server.js` change **_`<DB_USERNAME>`_** with your DataBase UserName & **_`<DB_PASSWORD>`_** with your DataBase Password.

## To Run the App

node server.js

### Author

SHANSKAR BANSAL
