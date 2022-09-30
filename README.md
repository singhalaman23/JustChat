# JustChat
**JustChat** is a chatting web application made using HTML, CSS, Javascript, Node.js and Socket.io. Multiple users can join at the same time and have a group chat among them.

Currently, the nodejs backend is deployed on Heroku and the HTML/CSS frontend is deployed on Github pages. You can access the website using the link https://singhalaman23.github.io/JustChat-frontend/

But heroku servers can sometimes run into some problems, and also the free dynos (free deploying service) provided by heroku is also going to be revoked from 28th November 2022.
So, after that, it may happen that you will only be able to see the frontend of this website, and you will not be able to chat at realtime for that moment. So you may need to run the node server at your local computer.

For running the app in your local computer, you need to run the node server for the **server_side_backend** files in your local computer by running the command `npm start`.
( Obviously you need to have **node** and **npm** pre-installed on your system for doing this ! )

And you may also need to change the first line of the **client.js** file present in the **client_side_frontend** folder. 
The line that connects to the heroku backend will have to be commented and the line which connects to the local server should be uncommented. 

Also, in the **index.html** file, we need to change the script tag and remove the heroku backend website and replace it with the localhost.

Here are few snapshots from the website.
>Dialogue box that asks for the user to enter his/her name 

![Image 1](https://github.com/singhalaman23/JustChat/blob/main/justchatIMG1.png?raw=true)

>First user entered with the name "Aman"

![Image 2](https://github.com/singhalaman23/JustChat/blob/main/justchatIMG2.png?raw=true)

>Second user entered with the name "Saurabh"

![Image 3](https://github.com/singhalaman23/JustChat/blob/main/justchatIMG3.png?raw=true)

>Saurabh left the chat

![Image 4](https://github.com/singhalaman23/JustChat/blob/main/justchatIMG4.png?raw=true)

>Footer of the website

![Image 5](https://github.com/singhalaman23/JustChat/blob/main/justchatIMG5.png?raw=true)



Here are few snapshots of the website from a mobile device

![mobileImage 1](https://github.com/singhalaman23/JustChat/blob/main/mobilejustchatIMG1.png?raw=true)

![mobileImage 1](https://github.com/singhalaman23/JustChat/blob/main/mobilejustchatIMG2.png?raw=true)


***Thankyou for using the JustChat - Chatting application.
Have a nice day!***
