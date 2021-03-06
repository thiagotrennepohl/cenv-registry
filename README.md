# cenv-registry

[![Build Status](https://travis-ci.org/rodrigogs/cenv-registry.svg?branch=master)](https://travis-ci.org/rodrigogs/cenv-registry)
[![Code Climate](https://codeclimate.com/github/rodrigogs/cenv-registry/badges/gpa.svg)](https://codeclimate.com/github/rodrigogs/cenv-registry)
[![Test Coverage](https://codeclimate.com/github/rodrigogs/cenv-registry/badges/coverage.svg)](https://codeclimate.com/github/rodrigogs/cenv-registry/coverage)
[![Dependency Status](https://david-dm.org/rodrigogs/cenv-registry/status.svg)](https://david-dm.org/rodrigogs/cenv-registry#info=dependencies)
[![devDependency Status](https://david-dm.org/rodrigogs/cenv-registry/dev-status.svg)](https://david-dm.org/rodrigogs/cenv-registry#info=devDependencies)

**cenv-registry** implements an api to manage [cenv's](https://github.com/rodrigogs/cenv) environments.

### Environment variables
* **NODE_ENV**
  - default: **'development'**
* **PORT**
  - default: **3000**
* **HTTP_LOG_CONFIG**
  - default: **'dev'**
* **MONGO_DB**
  - default: **mongodb://localhost:27017/cenv**

### Development
> Have a mongodb instance running

> ```$ npm start```
or
> ```$ yarn start```

### License
[Licence](https://github.com/rodrigogs/cenv-registry/blob/master/LICENSE) © Rodrigo Gomes da Silva
