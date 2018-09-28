# Front-End Web Development with React/Redux

Coursera course final result. This single-page application use JavaScript ES6, Reactstrap for Bootstrap 4-based responsive UI design, React router, Flux architecture and Redux. [Read more about this course.](https://www.coursera.org/learn/front-end-react).

I learned in this course: 

* Client-side Javascript application development and the React library
* Various React features including components and forms 
* Reactstrap for designing responsive React applications 
* Redux to design the architecture for a React-Redux application.

## Install packages

    npm install

## Installing json-server on your computer

    npm install json-server -g
    
### Start json-server before you start the application

Go to the json-server folder and type the following at the command prompt to start the server:

    json-server --watch db.json -p 3001 -d 2000
    
This should start up a server at port number 3001 on your machine. The data from this server can be accessed by typing the following addresses into your browser address bar:

* http://localhost:3001/dishes
* http://localhost:3001/promotions
* http://localhost:3001/leaders
* http://localhost:3001/feedback

## Start the application

    npm start
    
## Build data to the dist folder

    npm run build

## Tests

This application does not include any test. 

