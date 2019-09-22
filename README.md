# React Training: Resources

## Contents

 - [Working Mode](#working-mode)
 - [Environment](#environment)
 - [Online Shop](#online-shop)
 - [0. HTML and CSS Basics](#0-html-and-css-basics)
 - [1. React Intro](#1-react-intro)
 - [2. Components](#2-components)
 - [3. SCSS](#3-scss)
 - [4. Routing](#4-routing)
 - [5. Basic Redux](#5-basic-redux)
 - [6. Recompose](#6-recompose)
 - [7. Lazy loading]()
 - [OPT-1. Normalized Redux]()
 - [OPT-2. Internationalization]()
 - [OPT-3. Unit Testing](#opt-5-unit-testing)
 - [OPT-4. E2E Testing](#opt-6-e2e-testing)

## Working Mode

The road-map consists of several steps. In each step, a set of theoretical concepts are explored, supported by reference documentation, book chapters, tutorials and videos. In parallel, a simple application will be built with the learned concepts: the *Online Shop* application.

After the learning material for a given step was sufficiently explored, either some new functionality will be added to this application or old functionality will be refactored.

All the code written must be published on GitHub. Access the [this link](https://classroom.github.com/a/9-YuAfD4) to create your own repository. Commits must be pushed when each individual chapter is finished. In order to request a code review from the trainers, you must [open a pull request](https://help.github.com/en/articles/creating-a-pull-request) from the `develop` to the `master` branch.

## Environment

You can work using your local environment:
 - You need to install [NodeJS](https://nodejs.org/en/) and [VSCode](https://code.visualstudio.com/download).

In the `backend` folder you can find a server-side implementation for the online shop. Tu run this server perform the following:
 - Open the `backend` folder in your terminal
 - `npm ci` (only needed the first time your run the server)
 - `npm start`
 - Open [http://localhost:3000](http://localhost:3000) in your browser.

## Online Shop
The application will simply browse through a catalog of products. It will support:

 - Listing the products,
 - Adding a new product,
 - Updating an existing product,
 - Deleting a product.
 
The online shop has a "shopping cart" functionality:
 - The user may add items into the cart,
 - He may increment and decrement the quantity of each product or even remove a product completely from the cart,
 - Lastly, he may checkout the cart and place an order (resulting in the creation of an order in the backend).

Mockups describing the user interface structure can be found in the [mockups](./mockups/mockups.pdf) folder.
These mockups should be used as a guideline, but improvements or deviations from them is allowed. 

## 0. HTML and CSS Basics

Goal: refresh your knowledge about HTML and CSS basic concepts.

Required Reading:

 - [HTML Beginner Guide](https://www.htmldog.com/guides/html/beginner/)
 - [CSS Beginner Guide](https://www.htmldog.com/guides/css/beginner/)
 - [Git Basics](https://git-scm.com/book/en/v1/Getting-Started-Git-Basics)

Online Shop: *nothing to do*.

Further Resources:

 - [HTML and CSS Reference](https://www.htmldog.com/references/)
 - [CSS Media Queries](https://www.htmldog.com/guides/css/advanced/mediaqueries/)
 - [W3's Intro Tutorial](https://www.w3.org/Style/Examples/011/firstcss.en.html)
 - [GitHub - Hello World](https://guides.github.com/activities/hello-world/)
 
 ## 0. HTML and CSS Basics

Goal: refresh your knowledge about HTML and CSS basic concepts.

Required Reading:

 - [HTML Beginner Guide](https://www.htmldog.com/guides/html/beginner/)
 - [CSS Beginner Guide](https://www.htmldog.com/guides/css/beginner/)
 - [Git Basics](https://git-scm.com/book/en/v1/Getting-Started-Git-Basics)

Online Shop: *nothing to do*.

Further Resources:

 - [HTML and CSS Reference](https://www.htmldog.com/references/)
 - [CSS Media Queries](https://www.htmldog.com/guides/css/advanced/mediaqueries/)
 - [W3's Intro Tutorial](https://www.w3.org/Style/Examples/011/firstcss.en.html)
 - [GitHub - Hello World](https://guides.github.com/activities/hello-world/)

## 1. React Intro

Goal: become familiar with React.

Required Reading:

 - [Single vs Multiple Page Applications](https://medium.com/@NeotericEU/single-page-application-vs-multiple-page-application-2591588efe58)
 - [Create a New React App](https://reactjs.org/docs/create-a-new-react-app.html)
 - [React: Hello World](https://reactjs.org/docs/hello-world.html)

Online Shop:

 > Install *Create React App* with the help of the NodeJS package manager: `npm install -g create-react-app`.
 > 
 > Create a new project in the root of your git repository by using the CLI: `create-react-app online-shop`.
 > 
 > Navigate inside the project folder, start the project and open its home page in your browser: `npm start`.
 >
 > Install the [React Dev Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en) extension for Chrome. Inspect the application and view the components using this extension.

Further Resources:

 - [Tutorial: Intro to React](https://reactjs.org/tutorial/tutorial.html)
 - [How to see your React state and props in the browser](https://www.freecodecamp.org/news/how-to-see-your-react-state-props-in-the-browser-774098a50fcc/)

## 2. Components

Goal: get a grip on the basics of React Components.

Required Reading:

- [Introduction to JSX](https://reactjs.org/docs/introducing-jsx.html)
- [Rendering Elements](https://reactjs.org/docs/rendering-elements.html)
- [Components and Props](https://reactjs.org/docs/components-and-props.html)
- [Lists and Keys](https://reactjs.org/docs/lists-and-keys.html)
- [Styling and CSS](https://reactjs.org/docs/faq-styling.html#how-do-i-add-css-classes-to-components)

Online Shop:

 > For the moment, we will use mock data across all components. The data will be defined locally in the component's file.
 >
 > Create a new React Component for displaying a single product's details.
 >
 > Create an React component for displaying a list of products. Hint: use the `.map` call on the array of products.
 >
 > Add some CSS to each of the components to make them look nicer.
 
 Further Resources:
 
 - [The `.map` function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
 - [Why do I need Keys in React Lists?](https://medium.com/@adhithiravi/why-do-i-need-keys-in-react-lists-dbb522188bbb)
 - [React Virtual DOM Explained](https://programmingwithmosh.com/react/react-virtual-dom-explained/)
