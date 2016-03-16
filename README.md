## Yelp-Foursquare-Data-Mining
=============================================================
Built using Yelp, FS and Web3words APIs, Node.js, Express.js, MongoDB, Mongoose ODM

The app pulls data based on certain categories, in this case resturants from Yelp, and FourSquare, based on zipcodes in TX, and CA. Stores this data in Mongo, and runs a combo script to combine this data into a new instance(based on matched criteria). In addition to this, use the what3words api to apply a three word location for the hygiened records.

### Installation
=================
-- npm install
-- nodemon app.js