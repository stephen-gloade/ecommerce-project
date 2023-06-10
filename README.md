# Wearables E-Commerce Project

This repository contains the source code for a web-based e-commerce platform that specializes in wearable technology. This project was built to provide a user-friendly shopping experience for tech enthusiasts. 

## Project Overview

The platform allows users to view all items in the database, add items to a persistent shopping cart, and purchase items that are in stock. The shopping cart can be edited before completing a purchase, and all transactions update the database in real time.

The frontend of the application is built with React, providing a smooth and responsive user interface. The backend is built with Node.js, creating a RESTful API that interfaces with the frontend and a database.

The backend provides the frontend with all the required data in an organized and efficient manner. As users make purchases, the database is updated to reflect the current stock of items.

## Project Setup

Before diving into the code, follow these steps to set up the project:

1. Clone the repository to your local machine.

```bash
git clone https://github.com/stephen-gloade/ecommerce-project.git
```

2. Navigate into the project directory and install the dependencies.

```bash
cd server
yarn install
cd client
yarn install
```

3. Start the server.

```bash
cd server
yarn start
```

4. Start the client

```bash
cd client
yarn start
```

The application should now be running at `http://localhost:3000` (or your specified port).

## MVP

The project achieves the minimum viable product (MVP) by providing the following functionalities:

Frontend:
- Users can view all items in the database.
- Users can purchase items that are in stock.
- Users can view their cart containing the items they intend to purchase, and the cart persists across sessions.
- Users can edit the cart before completing the purchase.

Backend:
- The Node server provides a RESTful API.
- The server provides the frontend with required data in a clear and organized way.
- The server updates the database as users make purchases.

## Future Improvements

Here are some areas to improve in future development:

- Incorporate user accounts and authentication.
- Implement a review and rating system for products.
- Optimize database queries for better performance.
- Expand the product catalog with more categories of wearable tech.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE.md) file for details.
