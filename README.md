# Country API

Simple Node.js Express API that aggregates country data from public APIs and exposes endpoints your Discord bot can use.

## Endpoints
- GET /countries
- GET /country/:name
- GET /time/:name
- GET /compare?A=india&B=japan
- GET /random
- GET /continent/:region

## Run locally
1. Fill package.json dependencies: `npm install`
2. Start: `npm start`

Deploy to Render: push repo, create new web service, use render.yaml.
