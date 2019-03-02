+console
mkdir server
npm init -f  //makes package.json
npm install --save nodemon eslint   //for continuosly restart server
[20]: "scripts": {
          "start": ... "./node_modudules/nodemon/bin/nodemon.js src/app.js --exec 'npm run lint && node'",
          "lint": ... "./node_modules/.bin/eslint **/*.js"
eslint --init
../eslint.js --init
npm start
/src/app.js  console.log("hello"); //>hello

npm install --save express body-parser cors morgan                    //a couple deendencies
npm start

app.js
const express = require('express');
const bodyParser
const cors = require('cors');
const mogan

const app = express()
app.use(morgan('combine')
app.use(bodyParser.json())
app.use(cors())

app.get('status', (req, res) => {
     res.send({
          

app.listen(preocess.env.PORT || 8081)
