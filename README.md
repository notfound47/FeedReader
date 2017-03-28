## Feed Reader Testing

### Description:
The following project I wrote test suites that use [Jasmine](http://jasmine.github.io/) to validate my test suites.

### How to Run:
To run this application load the `index.html` file in your browser of choice, or from a terminal or command prompt window run the following python method to run as a web application `python -m SimpleHTTPServer 8080` and browse to `http://localhost:8080/`

### Tests Run:
1. allFeeds
* I wrote a test that loops through each feed in the allFeeds object and ensures it has a URL defined and that it isn't empty
* I wrote a tset that loops through each feed in the allFeeds object and ensures it has a name defiled and that it is not empty
2. The menu
* I wrote a test that ensures the menu element is hidden by default
* I wrote a test that the menu changes visibility when the menu icon is clicked to display and hide
3. Initial Entries
* I wrote a test that ensures when the loadFeed function is called and completes its work
4. New Feed Selection
* I wrote a test that ensures when a new feed is loaded by the loadFeed function that the content actually changes

### Sources:
https://jasmine.github.io/