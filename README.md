# Kookify-recipe-project
*Recipe applications with custom recipe uploads.*

![Screenshot 2024-07-08 132943](https://github.com/user-attachments/assets/6dc1f6ba-2ca9-4cc8-abbd-a6ee74c68ee9)

## Table of Contents

1. Description
2. Getting Started
3. References

### Description 
------------------------
The application provides the user with:
- Search for any recipe found in the API, where it will throw out all possible recipes for that dish
- If there are more than ten recipes, the recipes will be dynamically transferred to each subsequent page, until there are less than ten on that page
- Click on the desired recipe to view its ingredients
- Calculates the desired number of portions that the user chooses
- If the user likes the recipe, he will be able to save it, where the recipe will be saved in the storage, he will be able to see it every time he visits the application
- There is a possibility to upload a recipe, where the user will have to enter all the necessary ingredients

  ## The application provides the user with:
  ### Technologies
  - HTML
  - SASS
  - JS (API, OOP, AJAX)

  ### Getting Started
  ------------------------
  To start the project, it is necessary to download the files from the github, after that you must install npm and script in console.
  ## Instalation
  `npm install`
  `npm start`

  ### References
  ---------------------
  You can see the documentation for the api here, where you can find all the recipes you can search: [Forkify API v2 Documentation](https://forkify-api.herokuapp.com/v2)
  I made the application with the help of Jonas Schmedtmann in the JavaScript course: [JavaScript course](https://www.udemy.com/course/the-complete-javascript-course)

  ### API References
  - This function calls the recipes entered by the user
    `export const loadSearchResults = async function (query) {...};`
  - This function calls a recipe by its ID
    `export const loadRecipe = async function (id) {...};`
  - Through this function, we transfer the new recipe entered by the user to the server. It checks whether the data entered by the user is correct, if so, it uploads the data to the server
    `export const uploadRecipe = async function (newRecipe){...};`
  - Every contact with the server takes place through this function, whether you submitted the recipe on the server or requested its access from the server
    `export const AJAX = async function (url, uploadData = undefined){...};`
  
    
