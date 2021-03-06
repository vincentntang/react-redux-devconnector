MERN (Mongo Express React NodeJS) app demo for freelancers and clients with company profiles.

## Links

- [Wiki](https://github.com/vincentntang/MERN-Redux-SocialDevs/wiki)
- [LiveLink](socialdevs.herokuapp.com)

For test purposes, you can use "test@gmail.com/test12345" as "username/password"

## Installation

```
# Install dependencies for server
npm install

# Install dependencies for client
npm run client-install

# Run the client & server with concurrently
npm run dev

# Run the Express server only
npm run server

# Run the React client only
npm run client

# Server runs on http://localhost:5000 and client on http://localhost:3000
```

## Environmental folder

There is a `.env.sample` folder. Add your 4 keys there.

2 are for github auth (frontend)

another 2 are for mongoDB (backend)

## Pushing latest instance to Heroku

Install Heroku CLI

```
npm i -g heroku
heroku login
git remote add heroku https://git.heroku.com/socialdevs.git
# Stage latest commits (git add, git commit)
git push heroku master
```

## Current Features

- PrivateRoutes
- JWT Authentication
- CRUD operations

## Additional Feature List

- [ ] Swagger API Docs
- [ ] Jest Unit Testing
- [ ] Storybook
- [ ] TravisCI
- [ ] Docker Support

Upwork like functionality

- [ ] Clients
- [ ] Job Posts
