# Books.com

## v1.0.0   

Books.com is a web-based application that allows signed-in users to browse and order various books. The application is built using React for the frontend and Express for the backend, 
following the MVC (Model-View-Controller) design pattern. It provides a REST API to exchange data between the client and server. Data is stored in a Sqlite database.

## Features
* **Sign up**: Users must register with a unique e-mail address before accessing the website. Upon successful registration, the server generates a JWT and sends it to the user's browser as a cookie.
  
* **Login**: Users need to log in only after their JWT expires. If successful, a new token is generated and sent to the user's browser.
  
* **Browse Books**: Users can browse the available list of books in the store. Each book is displayed with its title, author and price.
  
* **Add to Cart**: Users can add selected books to their shopping cart. They can also adjust the quantity of book copies in the cart.
  
* **Order**: After adding books to the cart, users can proceed to the ordering process. To submit an order, user's address is required.
  
* **Viewing Orders**: Users can review all their orders. Order details include the date of the order, the books ordered, and the total price.    

## Built With  
* Typescript   
* React js
* Bootstrap
* Express js
* Sqlite
* Sequelize
* JWT (json web token)

## Installation    

1. Clone the repo
   
   ```sh
   git clone https://github.com/rabarbar15/books.com.git
   ```   
2. Go to project directory and build using Docker Compose
     
   ```sh
   docker-compose up --build
   ```
* Alternatively, you can run it with npm   
    
   Go to frontend directory and run
   ```sh
   npm run dev
   ```
   then in backend directory run
   ```sh
   npm run devStart
   ```

## App preview   

* Aplication will start on: `http://localhost:5173`
   
