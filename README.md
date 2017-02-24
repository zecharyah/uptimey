uptimey
=======

[![Build Status](https://travis-ci.org/stefanbc/uptimey.svg?branch=master)](https://travis-ci.org/stefanbc/uptimey) [![Dependency Status](https://dependencyci.com/github/stefanbc/uptimey/badge)](https://dependencyci.com/github/stefanbc/uptimey) [![Code Climate](https://codeclimate.com/github/stefanbc/uptimey/badges/gpa.svg)](https://codeclimate.com/github/stefanbc/uptimey)

If you're proud of your server uptime, because you put a lot of time into configuring it, then you can showcase it with **uptimey** - a beautiful server uptime monitor!

Just clone the repo on your web server and then access your server's host followed by `/uptimey`, in your browser. Simple as that!

Features
--

* The background image is a random image from [Unsplash](https://unsplash.com)!
* Works on Linux, Windows, Mac OS servers.
* Automatically gathers data from the server.
* Knows if it's nighttime or daytime.
* Knows the aprox server location (based on IP).
* Tweet your awesome uptime!
* Screenshot the server uptime and show it to your devops buddies! :)
* Configure it to your liking. You can modify the `client/bin/settings.json` file. Checkout the [SETTINGS.md](SETTINGS.md) file for more info on how to change the parameters.

![Screenshot](https://i.imgur.com/sbvuMBB.png)

Requirements
--

* PHP 5.5^
* Internet enabled server

Developers
--

Make sure you have Node 0.10^ and npm installed. You'll need to have Grunt and Sass installed. Use these commands:

```
npm install -g grunt-cli
gem install sass
```

You can then install all the project dependencies using:

```
npm install
```

Available Grunt tasks:

* `grunt` - will build the whole project.
* `grunt watch` - will watch for any file modifications and will build. Will also build on start.
* `grunt test` - will test the main app js file using `jshint` (more tests are coming soon).

For local development you can use Vagrant and you can check if the build passes using Travis-CI.
