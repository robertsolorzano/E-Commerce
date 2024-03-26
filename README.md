# E-Commerce ![License](https://img.shields.io/badge/License-MIT-blue.svg) 

## Description

A simple back-end application for an e-commerce website. It provides an API for managing products, categories, and tags. This application is built with Node.js, Express.js, and Sequelize, using MySQL as its database. It allows users to perform CRUD operations on the database through API endpoints.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Credits](#credits)
- [License](#license)

## Features

- View all products, categories, and tags
- View a single product, category, or tag by its ID
- Create new products, categories, and tags
- Update existing products, categories, and tags
- Delete products, categories, and tags

## Installation

1. Clone the repository:
```bash
git clone git@github.com:robertsolorzano/E-Commerce.git
```

2. Install the dependencies:
```bash
npm install
```

3. Seed the database:
```bash
npm run seed
```

## Usage

1. Start the server by running npm start in the terminal.
2. Open Insomnia and create a new request collection for the project.
3. Test the API endpoints by creating requests in Insomnia:
    - GET all items or a single item by ID
    - POST a new item
    - PUT to update an existing item
    - DELETE an item
4. Set the appropriate HTTP method, URL, and request body (if required) for each request.
5. View the API responses in the Insomnia interface to verify the success or failure of each operation.

**Make to sure create a .env file and configure all enviornment variables to it**

Video Demo: [Demo](https://www.youtube.com/watch?v=GeSne2XdyS8)

## Contributing

Contributors: [robertsolorzano](https://github.com/robertsolorzano)


## Credits

Starter code for this project:
[fantastic-umbrella - Xandromus](https://github.com/coding-boot-camp/fantastic-umbrella)


## License

This project is licensed under the MIT license. For more information, see [here](https://opensource.org/licenses/MIT).
  
