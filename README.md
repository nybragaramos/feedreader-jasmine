# FeedReader Project

This is a project from Udacity Fronend Nanodegree to test a [feedReader](http://github.com/udacity/frontend-nanodegree-feedreader) using [Jasmine](https://jasmine.github.io/).

## How to run this project?


### **First Option:**
* Use the project live link [here](https://nybragaramos.github.io/feedreader-udacity-nanodegree/)

### **Second Option:**
* Click "Download ZIP" and download the repository to your local machine
* Open the project folder
* Open index.html on your browser

### **Third Option:**
* **Pre-requisite:** Install node.js, npm, and git
* Clone the repository to your local machine
		````
		git clone https://github.com/nybragaramos/feedreader-udacity-nanodegree
		````
* Open the local folder of the repository at your bash terminal and run:
		````
		npm install
		````
* Run in a local server with the follow command at git bash:
		````
		gulp
		````
* Open http://localhost:3000/ in your browser.

## About the tests

* RSS Feed Suit
	* Ensures that the names and paths of the Feeds are correctly defined.
* The Menu Suit
	* Ensures that the menu element is hidden by default and that changes visibility when the menu icon is clicked.
* Initial Entries Suit
	* Ensures that when the loadFeed function is being properly called.
* New Feed Selection Suit
	* Ensures that when a new feed is loaded the content actually changes.

## Built With

[FeedReader](http://github.com/udacity/frontend-nanodegree-feedreader) - Inicial project
[Handlebars](https://handlebarsjs.com/) - JavaScript library
[JSAPI](https://google.com/jsapi) - JavaScript library
[jQuery](http://jquery.com/) - JavaScript library
[Jasmine](https://jasmine.github.io/) - JavaScript testing framework
[npm](https://www.npmjs.com/) - JavaScript package manager
[GulpJS](https://gulpjs.com/) - JavaScript toolkit
[Browser Sync](https://browsersync.io/) - Automation Tool

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

