# PWAtext
a text editor app that runs in the browser via a single-page application that meets the PWA criteria.


# User Story 
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use

# Acceptance Criteria 
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application


## Technical Acceptance Criteria: 40%
Satisfies all of the above acceptance criteria plus the following:
Uses IndexedDB to create an object store and includes both GET and PUT methods
The application works without an internet connection
Automatically saves content inside the text editor when the DOM window is unfocused
Bundled with webpack
Create a service worker with workbox that Caches static assets
The application should use babel in order to use async / await
Application must have a generated manifest.json using the WebpackPwaManifest plug-in
Can be installed as a Progressive Web Application

### Deployment 32%
Application deployed to Heroku at live URL with build scripts
Application loads with no errors
Application GitHub URL submitted
GitHub repo contains application code

#### Application Quality 15% 
Application user experience is intuitive and easy to navigate
Application user interface style is clean and polished
Application resembles the mock-up functionality provided in the Challenge instructions

##### Repository Quality 13%
Repository has a unique name
Repository follows best practices for file structure and naming conventions
Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.
Repository contains multiple descriptive commit messages
Repository contains a quality README file with description, screenshot, and link to deployed application

https://pacific-ridge-59829.herokuapp.com

<img width="1375" alt="Screenshot 2023-05-11 at 10 31 21 PM" src="https://github.com/xMaedayx/PWAtext/assets/120540407/0b2af147-a7b1-4d82-8d2d-8448a57b33d9">

