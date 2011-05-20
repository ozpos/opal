Opal: Ruby runtime for javascript
=================================

**Homepage**:      [http://opalscript.org](http://opalscript.org)  
**Github**:        [http://github.com/adambeynon/opal](http://github.com/adambeynon/opal)  

Description
-----------

Opal is a Ruby runtime and standard library designed to run directly on
top of javascript. It can be run within the browser or on the command
line through the bundled build tools. Opal includes a parser/compiler
that builds ruby ahead of time directly into javascript that runs with
the bundled runtime.

Installation
------------

Opal is distributed as a gem, so install with:

    $ gem install opal

Alternativley you can clone this repo with:

    $ git clone git://github.com/adambeynon/opal.git

Usage
-----

Opal can be used within in the browser, or on the command line using the
build tools. A Nodejs environment is also partially implemented.

To run within the browser, you can either use the latest build version
on the opal website, or clone the build tools as above, and then run the
following task in this directory:

    $ rake opal

This will place a non minified version ready to run within the browser
into `extras/opal.js`

Examples
--------

Examples can be found in the `examples/` directory in this repo, and
rely on `extras/opal.js` being created using the above commands.

