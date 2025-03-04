# social-network-api

  [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Description

    An API for a social network web application where users can share their thoughts, react to friend's thoughts, and create a friend list. This application was built using Express, Mongoose, and MongodB.
  
## Table of Contents

* [Description](#description)
* [Dependencies](#dependencies)
* [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)
* [Questions](#questions)

## Dependencies

  This project relies on the following dependencies:

* **Express**: Used to create the web server and define the API routes (endpoints) for your social network application.
* **Mongoose**: Used to define the data models (schemas) for users, thoughts, and reactions, and to interact with the MongoDB database.
* **Dotenv**: to load environment variables
* **MongoDB**: for the database
* **Date-fns**: Used for formatting date and time values (specifically createdAt) for thoughts and reactions in API responses.

## Installation

**Prerequisites:**

* Node.js and npm (or yarn) installed.
* MongoDB installed.

**Steps:**

1. Clone this repository
2. `cd` into the project folder
3. Install the dependencies by runnning `npm install` in the command line
4. With MongoDB installed, create the database `social-network-db`, and then run `npm run seed` to create and populate the documents and collections
5. `npm run dev` to test the server locally
7. `npm start` to start the production ready server

## Usage

[Video Demo](https://drive.google.com/file/d/1r3aVHzdKRshDrkL4P7BLAafrADCxd7ZK/view?usp=drive_link)

### Core Functionality

* APIs that: Create, Read, Update, and Delete users
* APIs that: Create, and Delete listed friends
* APIs that: Create, Read, Update, and Delete thoughts
* APIs that: Create, and Delete reactions

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are appreciated.



## License

  This project is licensed under MIT. For more information, see (<https://opensource.org/licenses/MIT>)

## Questions

  **GitHub**: [nolangrossi](https://github.com/nolangrossi)

  If you have any questions, please contact me at: <nolangrossi6@gmail.com>
  
