# King_StudentProfile

## Project Description
A Basic Student Profile application built for ITCC 41 (Mobile Application Development), created using HTML and CSS only, and packaged as an Android application using Apache Cordova.

## Application Structure

### Header
Contains a profile picture (avatar initials), full name, the "About Myself" subtitle, and the navigation menu.

### Navigation Menu
Two links — About and Skills — that jump the user directly to their matching sections further down the same page.

### About Section
Includes a section heading, two paragraphs introducing myself, my interests, my educational background, and my goals.

### Skills Section
Includes a section heading, five skills, and a short description under each one.

### Footer
Includes a copyright notice, my name, and the current year.

## Navigation
The About and Skills links in the navigation menu are plain HTML anchor links (`<a href="#about">`, `<a href="#skills">`) pointing to matching section IDs (`id="about"`, `id="skills"`) further down the page. No JavaScript is used — clicking a link scrolls the browser directly to that section, since both sections live on the same page rather than separate pages.

## How to Run
1. Install Node.js, then install Cordova globally: `npm install -g cordova`
2. Clone this repository and open the project folder in a terminal
3. Add the Android platform: `cordova platform add android`
4. Build the project: `cordova build android`
5. Start an Android emulator (via Android Studio's Device Manager), or connect a physical device with USB debugging enabled
6. Run the app: `cordova run android`

## Application Screenshot
![Student Profile running on Android emulator](screenshots/screenshot1.png)
![Student Profile running on Android emulator](screenshots/screenshot2.png)
![Student Profile running on Android emulator](screenshots/screenshot3.png)

## Author
Joshua King