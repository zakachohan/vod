# VOD
A simple Media App VOD (Video On-Demand) application.

## Layout:

### Header
Header has 2 parts Home and History

#### Home part is to fetch data from MOCK API.
#### History icon is abut videos which user watched recently.

### Content Section:
All data is shown in horientally with scroll bar and it becomes in 2 vertical line lsiting in responsive mod.

It also have refresh button to fetch data from API.
Also is uses "Font Awesome" to make more user firendly.

## Platform:
Can be run on any browser on WIndows,Linux, MacOS.


## DATA:
List of videos and their images coming from an MOCK API.
All videos are listed on horizentally with scroll bar.
User should be able to select a video and play it back in full screen and can exit using ESC key to home page.

## Previously watched:
User can see what was watched previously and these vides are sorted according to latest one at first number.

### Use of Mouse and Keyboard:
User can open videos using mouse and also by pressing enter keys on it.


## FOR GULP BUILD

1) Install NodeNode.js (Node) 

2) Now install Gulp
npm install gulp -g

3) Run the npm init
npm init
Complete all information required for Package.json file

4) Install Gulp into the project 
npm install gulp --save-dev

5) Run gulp file for test
gulp

6) Install Browser Sync for spinning up a web server 
npm install browser-sync --save-dev

7) Run and watch
gulp watch

It will automatically open application in your browser
Also you can see URL in CLI against ACCESS URL section

## Remaining Section:
Local saving of images.
Unit Tests.


## How to Run:
Open index,html file in any browser.

### Pre Requirements:
Browser (Chrome Preffered)
Good Internet connection
