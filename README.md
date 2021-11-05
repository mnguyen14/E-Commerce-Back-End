# E Commerce Back End

# Table of Content
[Description](#Description)

[Installation](#Installation)

[Usage](#Usage)

[License](#License)

[Contact](#Contact)

## Description
This allows the user to add, update, and delete categories, products, and tags of their choosing. They can also get all the categories, products, and tags or get them individually by id.

## Installation
Run 'npm install' in your terminal

## Usage
Run 'mysql -u root -p" in your terminal to log into your mysql. Then run 'SOURCE schema.sql;' to create the database.

Run 'node seeds/index.js' to add the seeds to your models. Then run 'node server.js' to begin using the app.

Here is a video demoing the app in Insomnia:
[![Demo of app](https://i.gyazo.com/242ef7c7ae057a818ef073066f48c4eb.png)](https://www.youtube.com/watch?v=fqZak3MNedI)

Deleting by id is the same for the other two models as well. However, for creating and updating, you will have to follow the columns layout found on the right-hand side of Insomnia or in the seeds folder for each of the models.

For example if I wanted to add a product, following the layout:

![product post layout example](https://i.gyazo.com/d7a9da71cea4ae6d10402016a6024b88.png)

It will return this product if you look it up by id:

![get product details by id after creating it](https://i.gyazo.com/42f67f67c1bb6c801cc5e1b1c34dde62.png)

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Contact
https://github.com/mnguyen14

Email: matthewnguyen0814@gmail.com