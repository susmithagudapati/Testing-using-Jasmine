# FEND-Feed Reader Testing Project

The aim of this project is to test my ability to use a library like Jasmine to write test suites and validating the code of feedreader project.

## About this application:
   * Includes a JSON object to configure a set of feeds - each having a name and url.
   * Provides a menu for users to change the selected feed to display.
   * Displays the headings of the articles from the selected feed in a list format with each providing a link through to           original article on this website.
   * Includes a Jasmine suite of tests for test-driven application development.

## Instructions

To view the feedreader website, download or clone the repository and open index.html in your browser.


## Tests

RSS Tests:
    * Feeds variable is defined and contains atleast one feed in it.
    * Feed URL is defined for every feed in feeds and is not empty.
    * Feed name is defined for every feed in feeds and is not empty.4

The Menu:
    * Menu hidden by default.
    * Menu changes visibility when the menu icon is clicked.

Initial Entries:
    * Feed container should contain atleast one entry.

New Feed Selection:
    * Content is changed when new feed is loaded by loadFeed.


## License

The project is licensed under the [MIT license](license.txt).

