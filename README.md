<h1 align="center">Blog Site and API using Express.js</h1>
<p>This project was made to show my kowledge of javascript modules such as node.js, ejs and express.js to produce web applications.</p>
<img src="https://github.com/user-attachments/assets/bb738a4b-7782-4d4c-be82-562be1564165">

<h3>How it works</h3>
I used express as my server application in this project which contains get and post routes, when the new post button is clicked the user gets redirected to a form where they fill in data about the post. 
When the post is created my express server in server.js sends a post request to my API in index.js to add the post. Posts can also be editted by clicking edit posts and changing the data, when this form is submitted it sends a patch request to the API which then changes the data.

<img src="https://github.com/user-attachments/assets/66339fae-9138-424f-b98f-f3b8934764b5">

The posts are currently stored in an array for the time being also. When the delete button is pressed a delete request is sent to the API and the post is found by id and removed from the array.
EJS was used to embedd the data from my javascript files into the website. I used nodemon when testing this site  as nodemon allows for changes to be updated immediately.

<h3>The API</h3>
I used axios to interact with my API, my API is RESTful as it allows for get, post, patch and delete requests at ease. In order for this project to be run you will need to download all files and use "npm i" in your terminall to install all required node packages.
You will then need to run both the index and server javascript filesm there will be no clashes or erros as they are both run on different ports.
