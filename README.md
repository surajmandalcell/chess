## Chess

Building a platform where people can

1. Sign up
2. Create a new match/get connected to an existing match
3. During the match, let users play moves
4. Have a rating system that goes up and down similar to standard chess rating

## Tech stack

Let's keep it simple

1. React for Frontend
2. Node.js for Backend
3. Typescript as the language
4. Saparate Websocket servers for handling real time games
5. Redis for storing all moves of a game in a queue

## How to run

1. Clone the repo
2. Run `yarn` in the root directory to install all dependencies
3. Setup DB
   - Create a `.env` file in the packages/db directory
   - Copy the contents of `.env.example` to `.env`
   - Fill in the values
4. Run `yarn dev` to start the server
