# Sweet Logger - a nice logger for your projects!

<a href="https://www.npmjs.com/package/sweet-logger"><img src="https://img.shields.io/npm/v/sweet-logger.svg?maxAge=3600" alt="NPM version" /></a>
<a href="https://www.npmjs.com/package/sweet-logger"><img src="https://img.shields.io/npm/dt/sweet-logger.svg?maxAge=3600" alt="NPM downloads" /></a>
<a href="https://github.com/uqlel/sweet-logger/"><img src="https://img.shields.io/github/repo-size/uqlel/sweet-logger" alt="Repo Size" /></a>
<a href="https://github.com/uqlel/sweet-logger/"><img src="https://img.shields.io/github/last-commit/uqlel/sweet-logger" alt="Last Commit" /></a>



![npm stats](https://nodei.co/npm/sweet-logger.png?downloads=true&stars=true)

## Table of contents
- [Installation](#installation)
- [Example usage](#example)
- [Help](#help)
- [Contributing](#contributing)
## Installation

Has been tested on NPM v6.14.11 and Node.JS
```bash
npm install sweet-logger
```

## Example usage

- Using class "log":
    - Importing:
        ```js
        global.log = require("sweet-logger").log
        ```
    - Usage:
        ```js
        log("Example info usage", "info")
        log("Example ready usage", "ready")
        log("Example error usage", "error")
        log("Example warn usage", "warn")
        log("Example debug usage", "debug")
        log("Clear console.log")
        ```
- Using log type classes
    - Importing:
        ```js
        global.logger = require("sweet-logger")
        ```
    - Usage:
        ```js
        logger.info("Example info usage")
        logger.ready("Example ready usage")
        logger.error("Example error usage")
        logger.warn("Example warn usage")
        logger.debug("Example debug usage")
        logger.clear("Clear console.log")
        ```

## Help

For help, contact me on Discord: [uQlel but better#3129](https://discord.com/users/822461337120538654), or by e-mail: root@uqlel.cf

## Contributing

You can add something to this package and help me, pull requests are welcome on Github Repository: https://github.com/uqlel/sweet-logger

*README inspired by the discord.js module*