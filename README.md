# Redux Store

# Table of Contents

[Description](#description) -
[Install](#install) -
[Usage](#usage) - 
[Links](#links) - 
[Contact](#contact) -
[Technologies](#technologies)

## Description

This app was designed using Context API and the goal was to modify the code to use Redux instead. This was done by creating a new store.js that would created a redux store using the already created reducers file. Doing this allows for the initial state to be changed from being passed in the GlobalState to being passed in with the reducers, this also changes how the reducers needed to be exported as well. The next change was to the Provider in app.js to use the react-redux Provider and passing in the new store from store.js. The final step was changing the state and dispatch in different component files to useDispatch or useSelector from react-redux instead. This allows the app to use Redux instead of Context API

## Install

Please use **'npm i'** in the command line to install the dependencies.

## Usage

When ready use **'npm run develop'** into the command line to run.

## Links

![Screenshot of App](./assets/website-screenshot.jpg) <br>
[Walkthrough Video](https://youtu.be/UTDLVyr3BlA) <br>
[Deployed App](https://cryptic-falls-36875.herokuapp.com/) <br>
[GitHub](https://github.com/niklasertle/nje-redux-store)

## Contact

[GitHub Profile](https://github.com/niklasertle)<br>
[Email Me](mailto:nik.ertle16@gmail.com)

## Technologies

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Apollo-GraphQL](https://img.shields.io/badge/-ApolloGraphQL-311C87?style=for-the-badge&logo=apollo-graphql)
![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)