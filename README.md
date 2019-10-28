# DevQ-Backend

## Description

This is the backend for an App called DevQ, and is deployed on heroku. To add additional questions, do so from the front end: https://wtsia.github.io/DevQ/. 

## Endpoints by Type:

HTML:

<code>https://immense-citadel-86220.herokuapp.com/HTML</code>

CSS:

<code>https://immense-citadel-86220.herokuapp.com/CSS</code>

JavaScript:

<code>https://immense-citadel-86220.herokuapp.com/JavaScript</code>

Express:

<code>https://immense-citadel-86220.herokuapp.com/Express</code>

React:

<code>https://immense-citadel-86220.herokuapp.com/React</code>

Node:

<code>https://immense-citadel-86220.herokuapp.com/Node</code>


## Backend Tech used:

Mongoose, Express, Node. <br /> 

## Local Installation:

Clone down the repo:

<code>git clone https://github.com/wtsia/DevQ-Backend.git</code>

Install the packages:

<code>npm install</code>

In two separate terminals in the root directory, run:

<code>mongod</code>

<code>nodemon</code>

To reseed the database, from inside the root directory:

<code>node db/seed.js</code>

Visit the local site at: 

<code>localhost:4000</code>

# CONTRIBUTION

To submit additional questions to the database, add your question in the array following the format:
<code>
{
  "question": "question",
  "hint": "hint",
  "answer": "answer",
  "url": "URL",
  "type": "language"
}
</code>

