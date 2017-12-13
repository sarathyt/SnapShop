
This is an retail application demonstrating the components needed for a Single Page Application using MongoDB, ExpressJS, Angular 2, and NodeJS.

Requirements

NodeJS
MongoDB
@angular/cli
Description

This applications demonstrates how to setup a RESTful API using NodeJS with Angular 2 Frontend. The application features a products view and ability of the user to add the product to cart.

Installation

Install all dependencies in package.json file. This can be done by navigating to the root directory in the command line interface and running the following command:
$ npm install
$ npm angular- material


Next, install all of the Angular 2 development dependencies in package.json file:

$ cd snapshop/

$ npm install
// add your npm installs required

Next, install all of the server dependencies in package.json file:


$ cd snapshop-server/

$ npm install express --save 

$ npm install mongoose 


Installation is complete. Navigate to the root directory and then:  
Production

-- In root directory(in snapshop_server):

$ npm run start

-- Access production server at: http://localhost:3000

Development

$ cd client/
$ ng serve
-- In another window, from root directory run:

$ npm start
-- Access development server at: http://localhost:4200
-- Access API at: http://localhost:3000


Contributors
AJ
Jigar
Hiren
Pranesh
Tarangini

No license.
