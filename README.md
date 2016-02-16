# Node.js Web Scraper

## Goal:
Create a command line program that can parse remote pages, read the html, and write the content that we care about to a file on disk.

## Project:
Create a node module to parse a remote webpage. Using npm to install third party modules used from the command line or as part of our own module. Also use npm to manage our modules' third party dependencies.

Next, create our own program/module that runs inside our terminal using node. The module will be designed to make HTTP GET requests to remote web pages and download their HTML.

Then (using yet another module), parse the HTML and write the content we are interested in to a file on disk.

## Setup:
After the initial setup (npm init and npm install --save \<libraries\> eg. __request__ and __cheerio__), create a module that will make an HTTP GET request to http://substack.net/images/, parse the page's html and write a file to disk called __images.csv__ that has 3 columns populated from the remote html. The columns should be:
* File Permission
* Absolute URL
* File Type