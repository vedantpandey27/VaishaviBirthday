VAISHNAVI BIRTHDAY WEBSITE — V2

EDIT ONLY script.js > CONFIG AT THE TOP.

1. PASSWORD
password: "12-09-2026"
Use DD-MM-YYYY. Change it whenever you want.

2. BACKGROUND IMAGE
Put your JPG/PNG inside the assets folder and set:
backgroundImage: "assets/background.jpg"
The CSS automatically uses cover/background positioning so it works on phone and PC.

3. MUSIC
Put an MP3/WAV inside assets and set:
music: { src: "assets/birthday.mp3", volume: 0.45, autoplayAfterFirstInteraction: true }
Important: modern browsers generally block audible autoplay on a page visit. The site therefore starts the music after the first tap/click. A small Music On/Off button is also provided.

4. PHOTOS
There are exactly 11 photo slots. Put your photos in assets/photos and use paths such as:
assets/photos/photo1.jpg
They appear ONE AT A TIME with a Show More button.

5. GIFS
Paste direct GIF/image URLs into gifLinks. A direct media URL is more reliable than a share/redirect URL.

6. FINAL MESSAGE
Edit finalMessage at the top.

TESTING
Open index.html in a browser or use VS Code Live Server.

NOTE
The password is a front-end gate, not real security. Anyone with the website files can inspect it.


V4 UPDATE - RUNAWAY NOT YET BUTTON
- On the second question, the "Not yet..." button now runs away when the pointer/finger gets near it.
- It is intentionally non-clickable and jumps to random positions inside the question area.
- Works with mouse and touch/pointer events, with extra proximity detection for phones.
- To change the button text, edit the second question's `no` value in script.js.
