# Modern Web UI - Website API

[![Build Status](https://travis-ci.org/modernwebui/api.svg?branch=master)](https://travis-ci.org/modernwebui/api)
[![Code Climate](https://codeclimate.com/github/modernwebui/api/badges/gpa.svg)](https://codeclimate.com/github/modernwebui/api)
[![Test Coverage](https://codeclimate.com/github/modernwebui/api/badges/coverage.svg)](https://codeclimate.com/github/modernwebui/api/coverage)
[![Dependency Status](https://david-dm.org/modernwebui/api.svg)](https://david-dm.org/modernwebui/api)
[![devDependency Status](https://david-dm.org/modernwebui/api/dev-status.svg)](https://david-dm.org/modernwebui/api#info=devDependencies)


An API for the [ModernWebUI website](https://github.com/modernwebui/website), based off of [Banker](https://github.com/truenorth/banker)

## Installation

### Requirements
* Node.js (`v0.12.2` or higher reccomended)

Install all dependencies via npm
```shell
npm install
```

Create a configuration file, with a `REDIS_URL` environment variable

**/.env**

```shell
export REDIS_URL=redis://......
```

Start the server
```shell
npm start
```

