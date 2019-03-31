# Selit! API OpenAPI Specification
[![Build Status](https://travis-ci.org/unizar-30226-2019-07/API.svg?branch=master)](https://travis-ci.org/unizar-30226-2019-07/API)
## Links

- [Reference Documentation (ReDoc)](https://unizar-30226-2019-07.github.io/API/)
- OpenAPI Raw Files: [JSON](https://unizar-30226-2019-07.github.io/API/openapi.json) [YAML](https://unizar-30226-2019-07.github.io/API/openapi.yaml)

**Warning:** All above links are updated only after Travis CI finishes deployment

## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and run `npm install` in the repo root

### Usage

#### `npm start`
Starts the development server.

#### `npm run build`
Bundles the spec and prepares web_deploy folder with static assets.

#### `npm test`
Validates the spec.

#### `npm run gh-pages`
Deploys docs to GitHub Pages. You don't need to run it manually if you have Travis CI configured.
