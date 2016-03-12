# Feed Reader Using Jasmine to Test

Tests were added in `jasmine/spec/feedreader.js` to test for functionality of the website.  The following tests are included:

- RSS feeds are defined in `allFeeds` and are not empty.
- Each feed in `allFeeds` has a defined and valid (simple RegExp) URL.
- Each feed has a defined and non-blank name.
- The navigation menu is hidden by default (on page load).
- The nav. menu toggles visibility after clicking the menu icon.
- The first feed has at least one entry.
- The feed changes content after selecting a new feed.

Two Additional Test Functions
- JavaScript URL validation, Credit: http://stackoverflow.com/questions/18364404/javascript-url-validation-regex
- JavaScript Empty String Check , Credit http://stackoverflow.com/questions/154059/how-do-you-check-for-an-empty-string-in-javascript

## Getting Started

Download or clone the repository and open it in your browser locally.  All needed Jasmine libraries are included, and you will see a section below the page showing the test results.

To add or edit the feed sources, open `js/app.js` and change the `allFeeds` object.  Ensure that you have at least 2 feeds, or else the 'New Feed Selection' test will fail.

### Prerequisites

All the prerequisites are pre-install in the web page so that the user don’t need to do anything on there computer but a browser is a must and I will suggest updating the browser to the latest version. 

### Installing

You only Need a Browser like chrome or Firefox, or IE but lasted version preferred.


## Running the tests

When feeds are loading into the web browser, the test will automatically run and give feedback on the bottom about what has been run and reported results.

## Deployment

I deploy this app to github platform. you can access web app through this link: http://vncling.github.io/Udacity-Map-Project/index.html

## Built With

* Dreamweaver
* Jasmine


## Versioning

I use Github for versioning purpose

## Authors

* **Vincent Ling** - *Initial work* 


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Special thanks to Udacity Teaching staffs and teaching materials
* All internet resources specially in github and Stack Overflow
