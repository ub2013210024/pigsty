# pigsty
This is our Software Engineering Project using mongodb to connect to a pig monitoring system. 

Getting Started

You will need an Atlas MongoDb Account. Login to your account and create a new connection. Get your mongo-driver module and use it to connect to MongoDb from your go program.

![image](https://user-images.githubusercontent.com/123121590/229192181-5a199726-cf97-4738-9487-b66012e01e46.png)


First, run the server:

go run main.go

Install

Install visual studio extension, Thunder Client.
 
 Create a New Request and type in local houst rout, example:
 http://localhost:4000/api/
 
 Navigate into the tab "body" and under the json field, type in the json string to insert new room and press "Send".
 ![image](https://user-images.githubusercontent.com/123121590/229192541-7afdb8df-063d-49d4-8756-9fcf69c18eaf.png)

 
 Terminal should indicate that the new room was added into the database.
 ![image](https://user-images.githubusercontent.com/123121590/229192321-d39da85b-7540-438f-9b97-57b7368d32de.png)

 
 Entry should be seen inside MongoDb. 
 ![image](https://user-images.githubusercontent.com/123121590/229192048-ec70f287-b1b9-496a-a1eb-4e062c5ba431.png)

 


