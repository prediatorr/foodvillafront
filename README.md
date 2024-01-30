# Getting Started with Create React App


GoFood - Full Stack Food Ordering Website.

GoFood is a full-stack food ordering website built on the MERN stack, allowing users to easily order food online. The website provides user authentication and authorization using BCrypt.js and JSON Web Tokens (JWT). Users can create their accounts, log in securely, and place food orders. Additionally, users can view their previous orders from the "Your Orders" section.

#Features
User Authentication: Users can create accounts and log in securely using BCrypt.js for password hashing and JWT for authentication.
Order Placement: Users can browse food items, add them to the cart, and place orders securely.
Order History: Users can view their previous orders and order details from the "Your Orders" section.
Responsive Design: The website is designed to be responsive, providing a seamless experience across devices.

#Technologies Used
MongoDB: NoSQL database used to store user information, food items, and order history.
Express.js: Backend web framework for handling API requests and routing.
React: Frontend library for building user interfaces and components.
Node.js: JavaScript runtime environment for running server-side code.
BCrypt.js: Library for hashing passwords securely.
JSON Web Tokens (JWT): Authentication tokens used for user authentication and authorization.
HTML5 & CSS3: Markup and styling languages for structuring and designing the website.
Bootstrap or Material-UI: CSS frameworks for responsive and visually appealing design.

#Folder Structures
GoFood/
│
├── backend/        # Backend server code
│   ├── controllers/    # Route controllers
│   ├── models/         # Mongoose models
│   ├── routes/         # Express routes
│   ├── utils/          # Utility functions
│   └── server.js       # Express app setup
│
├── frontend/       # Frontend React app
│   ├── public/         # Static assets
│   └── src/            # Source files
│       ├── components/    # React components
│       ├── pages/         # Page components
│       ├── context/       # React context for state management
│       ├── hooks/         # Custom React hooks
│       ├── services/      # API service functions
│       └── App.js         # Main React component
│
├── .gitignore      # Git ignore file
├── README.md       # Project README file
└── package.json    # NPM package configuration


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
