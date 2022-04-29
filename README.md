# pwa-text-editor

##Intro
This is my pwa text editor! With it you can edit some text! Make sure to install with `npm install` in both the server and client folders and the root. 

##Link
Heroku Deployed Link: https://note-taker-pwa-homework.herokuapp.com/


##Images
Working as a PWA
![pwa](https://user-images.githubusercontent.com/71856810/165899310-3bbe32a3-55d9-45fb-b0d5-05af2ce7b6dc.PNG)

Manifest JSON
![pwa manifest](https://user-images.githubusercontent.com/71856810/165901504-d1d719ce-3ec7-4354-ab5b-ab57e1a79396.PNG)

Index DB
![pwa indexdb](https://user-images.githubusercontent.com/71856810/165906888-cab12380-1fc6-4e77-b626-09ffa1fd010c.PNG)

## Acceptance Criteria

```md
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
```
