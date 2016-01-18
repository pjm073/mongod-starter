# mongod-starter ![](https://img.shields.io/github/release/gmontalvoriv/mongod-starter.svg) ![](https://img.shields.io/github/commits-since/gmontalvoriv/mongod-starter/1.0.0.svg)

<img align="right" height="300" width="300" src="https://github.com/gmontalvoriv/mongod-starter/blob/master/images/logo.png" />

## Overview

**mongod-starter** is a menu bar application for starting your local **MongoDB** server. With this utility you will also be able to save your `mongod`, data storage, and configuration file directories allowing you to have a more consistent setup.

## [Download](https://github.com/gmontalvoriv/mongod-starter/releases)

<br>
## Screenshot

<img align="right" height="335" width="900" src="https://github.com/gmontalvoriv/mongod-starter/blob/master/images/Screenshot.png" />

## Requirements

- OS X 10.10
- [MongoDB](https://www.mongodb.org/downloads#production)

## Installation

1. Copy "mongod-starter.app" to /Applications
2. Run from there
3. Optionally drag into "Login Items" under "System Preferences"/"Users & Groups" to autostart on login

## Configuration

1. Go to Preferences
2. Setup `mongod` and data storage locations
3. Optionally add your `mongod` configuration file 

### Homebrew users

> After installing MongoDB with **Homebrew**:

- The databases are stored in the `/usr/local/var/mongodb/` directory
- The mongod.conf file is here: `/usr/local/etc/mongod.conf`
- The mongo logs can be found at `/usr/local/var/log/mongodb/`
- The mongo binaries are here: `/usr/local/Cellar/mongodb//bin`

## Acknowledgements

mongod-starter.app icon done by [Melanie De Jesús](mailto:melanie.dejesus92@hotmail.com) • [Instagram](https://www.instagram.com/cybertrousers/).

## License

[MIT](https://github.com/gmontalvoriv/mongod-starter/blob/master/LICENSE) © Gabriel Montalvo

