# Demo of custom/blurry Backgrounds for Vonage
Deployed using render.com at:
https://vonage-backgrounds-demo.onrender.com/filter

Applying Client-side Filters using Google BodyPix library

1. add your opentok credentials in server.js. this demo uses a fixed session-id and generates tokens for this session-id
2. "npm install" to install dependencies
3. "npm start" to start the sever
4. http://localhost:8026/filter to open the webpage that uses filters

List of filters
1. Background blur - adjustable threshold
2. Color pop - converts background to greyscale while keeping the subject in color
3. Pixelate - pixelates background - adjustable threshold
4. Background image - replaces background with selected image
5. Background video - replaces background with live video - very CPU intensive 
