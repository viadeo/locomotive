# Maglev

[![Build](https://circleci.com/gh/viadeo/maglev.svg?style=shield)](https://circleci.com/gh/viadeo/maglev)
[![Coverage](https://coveralls.io/repos/viadeo/maglev/badge.svg)](https://coveralls.io/r/viadeo/maglev)
[![Code Climate](https://codeclimate.com/github/viadeo/maglev/badges/gpa.svg)](https://codeclimate.com/github/viadeo/maglev)
[![Dependencies](https://david-dm.org/viadeo/maglev.svg)](https://david-dm.org/viadeo/maglev)

Maglev is a framework that brings structure and MVC patterns to web
applications using [Node](http://nodejs.org) and [Express](http://expressjs.com/).

This repository is a GitHub fork of [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive).

## Installation

    $ npm install locomotive

## Quick Start

`maglev`, the command line interface to Maglev, can be used to generate a
starter application. To use it, install Maglev globally.

    $ npm install locomotive -g
    
Next, create an application and install dependencies.

    $ maglev create hello
    $ cd hello
    $ npm install
    
Start the server.

    $ maglev server

The application is available at [localhost:3000](http://localhost:3000).

Start the server with node debug mode

	$ maglev server --debug (node --debug mode)
	$ maglev server --debug-brk (node --debug-brk mode)

Then you can use debug tools like [node-inspector](https://github.com/dannycoates/node-inspector) to debug your application as usual.

## Guide

The [Locomotive Guide](http://locomotivejs.org/guide/) is the official source
for documentation, and is a handy reference to have available when developing
web applications powered by Locomotive.

## Datastore Adapters

<table>
  <thead>
    <tr><th>Adapter</th><th>Description</th><th>Developer</th></tr>
  </thead>
  <tbody>
    <tr><td><a href="https://github.com/jaredhanson/locomotive-mongoose">Mongoose</a></td><td>Mongoose ODM adapter.</td><td></td></tr>
  </tbody>
</table>

## Tests

    $ npm install
    $ make test

## Credits

  - [Jared Hanson](http://github.com/jaredhanson)

## License

(The MIT License)

Copyright (c) 2011 Jared Hanson

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
