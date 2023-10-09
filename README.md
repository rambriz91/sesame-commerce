# 13 Object-Relational Mapping (ORM): E-Commerce Back End

## Description

This app utilizes insomnia to allow users to view the e-commerce_db. The user can review all tags, products, and categories using an insomnia get request. The user can also create new tags, products and, categories. The user also has the ability to edit and delete data from the database by using put and delete requests after adding the id in the pathway.

## Tasks

- Created routes for products, categories, and tags
- fleshed out the models for products, categories, tags, and product tags.
- build associations between the models in the routes/api/index.js file.
- utilized POST, GET, PUT, and DELETE requests.

## Usage

User must first log into mysql to source the schema.sql file, then the user exits the mysql shell and runs the "npm run seed" command. After the data is seeded. the user can simply type npm start in the terminal to set up the server.

The server can be accessed by inputing http://localhost:3001/api/ in the insomnia search bar, followed by the queries, products, categories, or tags.

## Links

GitHub Repo Page: https://github.com/rambriz91/sesame-commerce

## Credits

https://www.npmjs.com/package/sequelize
https://www.npmjs.com/package/dotenv

## License

MIT License

Copyright (c) [2023] [Robert Ambriz]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
