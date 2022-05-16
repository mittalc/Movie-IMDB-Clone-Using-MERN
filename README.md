# iCine-MERN-App

Installation
Use the package manager npm to install iCinema. Setup the project and install the packages by running:

npm run setup
Run project with command

npm run dev
Built with
FrontEnd: React.JS, Redux Library, Bootstrap, HTML/CSS
Backend: Node.JS, Express.JS
Database: MongoDB, Mongoose
Features
Sign In / Sign Up / Sign Out the user.
Recieving a welcoming email when sign-up using Nodemailer.
Add a new movie to the list.
API
Users
POST /api/users/signup
POST /api/users/login
DELETE /api/users/:userID
Movies
GET /api/movies
POST /api/movies/addmovie
DELETE /api/movies/:movieID
Genres
GET /api/genres
POST /api/genres/addgenre
DELETE /api/movies/:genreID
