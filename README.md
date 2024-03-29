# Home Library Service

## Description
Let's try to create a Home Library Service! Users can create, read, update, delete data about Artists, Tracks and Albums, add them to Favorites in their own Home Library!

## Prerequisites

- Git - [Download & Install Git](https://git-scm.com/downloads).
- Node.js - [Download & Install Node.js](https://nodejs.org/en/download/) and the npm package manager.

## Downloading

```
git clone -b part-3 https://github.com/ylepner/nodejs2023Q2-service.git
```

## Installing NPM modules

```
npm install
```

## Running docker containers

```
docker-compose up
```
After starting the app on port (4000 as default) you can open
in your browser OpenAPI documentation by typing http://localhost:4000/api/.
For more information about OpenAPI/Swagger please visit https://swagger.io/.
## Testing

After application running open new terminal and enter:

To run all tests without authorization

```
npm run test:auth
```

## Auto-fix and format

```
npm run lint
```

```
npm run format
```

## Debugging in VSCode

Press <kbd>F5</kbd> to debug.

For more information, visit: https://code.visualstudio.com/docs/editor/debugging
