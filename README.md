# E-commerce 
## Description
This application will create a database which is able to store product data, along with category and tag data, for an e-commerce website
## Table of Contents
1. [Installation](https://github.com/rau1avi1a/E-commerce#installation)
2. [Usage](https://github.com/rau1avi1a/E-commerce#usage)
3. [License](https://github.com/rau1avi1a/E-commerce#license)
4. [Contributing](https://github.com/rau1avi1a/E-commerce#contributing)
5. [Tests](https://github.com/rau1avi1a/E-commerce#tests)
6. [Questions?](https://github.com/rau1avi1a/E-commerce#questions)
## Installation
In order to set up the database, run 'mysql -uroot -p', it will then prompt the user to input a password. After inputting the password, run 'source db/schema.sql;'. This command will create the database. In order to seed the databse, exit the mysql command line using 'quit', and then run 'seeds/index.js'. After data has been seeded, user can view data using insomnia.
## Usage
In order to use this application you will need Insomnia. To start the server, run 'npm start' in the command line. In Insomnia, set the route to http://localhost:3001. in order to view product data, append the route with /api/products. The process is the same for categories and tags (/api/categories or /api/tags). In order to view a specific id for any of these routes, append the route with the number id (ex: /api/products/2, will give second product). GET, POST, PUT, and DELETE methods are available. Watch the video for more information.
<iframe src="https://drive.google.com/file/d/1zJ-eEbHUHzBF6R0gN0GA3u_qmRvNQ4YJ/preview" width="640" height="480"></iframe>

## License
N/A
## Contributing
N/A
## Tests
N/A
## Questions?
Reach me on [GitHub](https://github.com/rau1avi1a)
