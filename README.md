# User_authentication_api built using express and mongodb
Have used bcryptjs for hashing the user password


Steps: 
clone the repo 
use Terminal to change the current working directory to the location where you have cloned the repo
#npm i <!-- #to install all the necessary packages--!>
ensure you have your mongodb server up and running
open server.js file and enter your database name in the 10th line of the file
example: 'mongodb://localhost:27017/trial' <!-- where trial is the name of the database and 27017 is the default port on which mongodb starts>
#node server.js <!-- to start the server--!>
open your browser and access the server which is up at port 9999
http://localhost:9999/index.html -> registration
http://localhost:9999/login.html -> login
http://localhost:9999/change-password.html -> change password

<!-- if port 9999 is busy, change the port number in the server.js file - line number 116 and 117>
