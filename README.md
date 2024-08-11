# E-Commerce Back End

## Description

This project provides the back end for an e-commerce website using Express.js and Sequelize ORM to interact with a PostgreSQL database. It includes a RESTful API for managing categories, products, and tags. The application supports creating, reading, updating, and deleting records, making it a solid foundation for an e-commerce platform.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
  - [Categories](#categories)
  - [Products](#products)
  - [Tags](#tags)
- [Walkthrough Video](#walkthrough-video)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. **Clone the repository:**
   ```bash
   git clone git@github.com:schneibley/homework-13-Ecommerce.git
   cd homework-13-Ecommerce
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Create a `.env` file in the root directory with your PostgreSQL credentials:**
   ```bash
   DB_NAME=your_database_name
   DB_USER=your_database_user
   DB_PASSWORD=your_database_password
   ```

4. **Create the PostgreSQL database:**
   ```bash
   psql -U "your-username"
   \i db/schema.sql
   ```

6. **Seed the database with initial test data:**
   ```bash
   node seeds/index.js
   ```

## Usage

1. **Start the server:**
   ```bash
   npm start
   ```

2. **Test the API endpoints using a tool like Insomnia or Postman:**

   - **Categories**
     - `GET /api/categories` - Retrieve all categories.
     - `GET /api/categories/:id` - Retrieve a category by ID.
     - `POST /api/categories` - Create a new category.
     - `PUT /api/categories/:id` - Update a category by ID.
     - `DELETE /api/categories/:id` - Delete a category by ID.

   - **Products**
     - `GET /api/products` - Retrieve all products.
     - `GET /api/products/:id` - Retrieve a product by ID.
     - `POST /api/products` - Create a new product.
     - `PUT /api/products/:id` - Update a product by ID.
     - `DELETE /api/products/:id` - Delete a product by ID.

   - **Tags**
     - `GET /api/tags` - Retrieve all tags.
     - `GET /api/tags/:id` - Retrieve a tag by ID.
     - `POST /api/tags` - Create a new tag.
     - `PUT /api/tags/:id` - Update a tag by ID.
     - `DELETE /api/tags/:id` - Delete a tag by ID.

## Walkthrough Video

[Walkthrough video here](https://drive.google.com/file/d/1vBgNOtF832lJ3lO6AezqzbXHIHiOO1vz/view)

## Contributing

Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

---
