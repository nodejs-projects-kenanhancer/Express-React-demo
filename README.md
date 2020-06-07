# Express-React-demo

## Creating Main Project Directory

Run the following command in your terminal.

```shell script
mkdir Express-React-demo
cd Express-React-demo
```

## Creating React App

Run the following commands in your terminal.

```shell script
npx create-react-app client
cd client
npm start
```

To verify your React app, in your browser, navigate to http://localhost:3000/

- C for Create: HTTP POST
- R for Read: HTTP GET
- U for Update: HTTP PUT
- D for Delete: HTTP DELETE

## Creating Express App

Run the following commands in your terminal.

```shell script
npx express-generator api
cd api
npm install
npm start
```

then update start script in `./api/package.json` file with `PORT=9000`. So it looks like the following line.

`"start": "PORT=9000 node ./bin/www"` 

To verify your React app, in your browser, navigate to http://localhost:9000/