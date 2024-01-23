pm# TECHNICAL TEST AXA BY ZOUHOUR BALLOUM

# GETTING STARTED

## setting up backend

Its a JSON-Server based Application, Generates Random Data for Stocks Evolution

### Install packages

```
npm run setupback
```

## setting up Front App

frontend App was created with React. You will need to Install the Dependencies in order to be able to start the application later

### Install packages

```
npm run setupfront
```

### Application Architecture

```

├── back
│   ├── api.js
│   ├── app
│   ├── index.js
│   ├── package-lock.json
│   ├── package.json
│   └── webpack.config.js
└── front
    ├── index.html
    ├── jest.config.cjs
    ├── package-lock.json
    ├── package.json
    ├── public
    ├── src
    ├── tests
    ├── tsconfig.json
    ├── tsconfig.node.json
    └── vite.config.ts
```

## starting the application

Start by running the Backend, then the front app using the commands below

```
npm run start-api
```

and to start the delay version

```
npm run delay-api
```

Then Start the front Application

```
npm run frontapp
```

# FUNCTIONALITIES

### Stocks Evolution

As the user and if the data is available, A Trendline chart is drawn to show the evolutions of stocks price

### Edit Data

When data are available, an editable table is displayed with every key value so you can edit and see the results live on the chart.


### Handle of Errors and cache

If the API is not available a Message showing the **Exact Issue** is displayed, also if the data was cached before, the data **Will load automatically** from the cache of the browser



### Tests

The frontend applications contains unit tests to ensure the correct rendering of the components. You can run the Tests using: 

```
npm run test
```
