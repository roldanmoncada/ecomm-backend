# Ecomm Backend

## Description:

This application is an ecomm backend that contains several categories, products, product tags, and tags. Each of these aforementioned items are models that adhere to the following associations:

`A given Product belong to a single Category, but a Category can have multiple different products.`

`A given Product belongs to many Tag models. With these two models, we use a through model called ProductTag which allows Products to have multiple Tags and Tags to have many Products.`

Category, Product, and Tag API routes have also been created for the purpose of performing RESTful CRUD Operations.

The functionality of this application will be explained via video clip as requested by the assignment's Grading Requirements.

The assignment's User Story and Acceptance Criteria can be found in their own sections below.

## User Story:

```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria:

```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```

## Screenshots:

This application will not be deployed and requires a video guide so I will not be including too many screenshots.

The application has the capability to perform all RESTful CRUD operations, as previously mentioned. All will be displayed in my video guide, but below you can view the full list and the results of the GET route for all Categories.
![image](https://user-images.githubusercontent.com/112277445/215362705-20c1ba6f-6e78-4fd9-9a74-f1ff54ff6907.png)

Here is the result of the GET route for all Products:
![image](https://user-images.githubusercontent.com/112277445/215362631-6dbdbda5-dc6e-4876-b18c-d7c772c53349.png)

Here is the result of the GET route for all Tags:
![image](https://user-images.githubusercontent.com/112277445/215362670-6df45987-ae9f-4caa-9f70-c03c851b0d4b.png)

## Deployment Links:

Here is a link to my GitHub [repo!](https://github.com/roldanmoncada/ecomm-backend)

Here is the live [app!](https://roldanmoncada.github.io/ecomm-backend)
