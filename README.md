# Full-Stack Web Application：Personal Finance Tracker

## Technologies Used:

Node.js, Express.js, MongoDB, React, Redux, Bootstrap, Firebase Authentication

## Description:

Developed a personal finance tracking application that allows users to manage their expenses, set budgets, and visualize their financial health through interactive charts.

## Key Responsibilities:

### Backend Development:

- Designed and implemented RESTful APIs using Node.js and Express.js to handle user authentication, data retrieval, and transactions.
- Integrated MongoDB for data storage, ensuring optimal schema design for efficient querying and data management.

### Frontend Development:

- Built a responsive user interface with React, utilizing Redux for state management to enhance user experience and application performance.
- Implemented Bootstrap for styling, ensuring a mobile-first design that adapts to various screen sizes.

### Authentication and Security:

Implemented user authentication using Firebase Authentication, allowing secure sign-up and login processes.
Ensured data security by validating user inputs and implementing middleware for authentication checks.

### Data Visualization:

Integrated Chart.js to create dynamic visual representations of user spending habits, enabling users to make informed financial decisions.

### Deployment and Maintenance:

Deployed the application on Heroku, managing environment variables and ensuring smooth production operations.
Conducted regular maintenance and updates based on user feedback and bug reports.

![expense-tracker](/public/photos/expense-tracker.gif)

## Features

- Sign up an account
- Log in
- View all expenses/revenues
- View total amount of balance
- View expenses break down by category and month in chart visualizations
- View monthly spent and remaining budget in pie chart
- Filter expenses by category and month
- Filter revenues by month
- Add an expense and a revenue
- Edit their expense, revenue, budget, avatar, and name
- Delete an expense and a revenue
- Log out of an account

![Login page](/public/photos/login-new.png)
![Register page](/public/photos/register-new.png)
![Expenses page](/public/photos/expenses.png)
![Revenues page](/public/photos/revenues.png)

## Prerequisites

- [Git](https://git-scm.com/downloads)
- [Node.js v14.15.1](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [mongoDB](https://www.mongodb.com/)

## Install Expense Tracker

#### Clone the repository locally

```
$ git clone https://github.com/ivyhungtw/expense-tracker.git
```

#### Install project dependencies

```
$ cd expense-tracker
$ npm install
```

#### Add .env file

To properly use the app and Facebook login feature, make sure you have filled out the following information in .env file.

You can get your own Facebook id and secret on [Facebook Developers](https://developers.facebook.com/).

## Use Expense Tracker

#### Import seed data

To have default users, categories, and records set up, run the following script.

```
$ npm run seed
```

#### Start the app

If you have installed [nodemon](https://www.npmjs.com/package/nodemon), run the following script.

```
$ npm run dev
```

or just run:

```
$ node app.js
```

The server will start running on http://localhost:3000/
