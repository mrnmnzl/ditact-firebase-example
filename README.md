# ditact-firebase-example
A simple chat app with authentication using firebase by Marion Menzl

Instructions: 
* Install Firebase CLI `npm install -g firebase-tools`(make sure you have NPM installed)
* Create a new Firebase Project within the Firebase console
* (!) To use the google Login: Under Develop > Authentication > (Signin) methods you need to activate Google Provider
* (!) To use the database: Under Develop > Database > Scroll down to "Decide for a Realtime Database" and click "Create Database" and (!) then choose "test mode", otherwise calls to the db will fail
* In your terminal use `firebase init hosting` (it might ask you to sign in with your google account)
* Choose the project you already created in the console (choose public as folder and yes if asked for redirects to index.html)
* Clone or download this project and copy the content of the index.html file into the created one for your project, and copy the styles.css file into your public folder (where your index.html file is)
* From this point on and if everything worked, you can use `firebase serve` which starts a server on localhost:5000 (if this command fails: add --project [your-project-name])
* If you are done with editing, you can try to deploy your project with `firebase deploy`
* The project is now available for all users under the domain you can find in your terminal

All these steps are necessary because I will disable my database used for the lecture.

The powerpoint presentation can be found on the Ditact website on the page of this lunch lecture.
I really hope the lecture was helpful to you.
