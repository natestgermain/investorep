# Investorep
Make smarter investment decisions based on the reputations of others.

## Run locally
A .env file containing database credentials, api keys, etc. is required for
running this site. An example .env file can be found in the root directory as
.env.example

```
npm install
npm start
```

Manually run Express and dev server(optional)
```
ng serve --proxy-config proxy.config.json
nodemon server/app.js --watch server
```

Detailed views of the running scripts can be found in package.json
