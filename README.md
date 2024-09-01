# Roughpad
A very simple HTML page to take quick note.

## How to run

### Dev server
```(shell)
yarn start
# will start dev server on http://localhost:1234
```

### Build
```(shell)
yarn build
# will create a production build in the `dist` directory
```

### Serve
```(shell)
yarn serve
# will run a server from the directory on http://localhost:9009
```

### Run as a background process
Install `pm2` by running `npm i -g pm2@latest` or `yarn add -g pm2@latest`
Then from inside the project directory
```(shell)
yarn build
pm2 start ./ecosystem.cofig.js
```

This will add the the server as a pm2 process in background and is accssible from `http://localhost:9009`

## Features
- Automatically saves notes in local storage
- _New features will be added_
    - Control dashboard
    - Manual save/clear storage
    - Last saved/modified timestamp
    - Export/import