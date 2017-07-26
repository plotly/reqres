<!-- README.md is generated from README.Rmd. Please edit that file -->
reqres
======

[![Travis-CI Build Status](https://travis-ci.org/thomasp85/reqres.svg?branch=master)](https://travis-ci.org/thomasp85/reqres) [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/thomasp85/reqres?branch=master&svg=true)](https://ci.appveyor.com/project/thomasp85/reqres) [![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version-ago/reqres)](https://cran.r-project.org/package=reqres) [![CRAN\_Download\_Badge](http://cranlogs.r-pkg.org/badges/reqres)](https://cran.r-project.org/package=reqres) [![Coverage Status](https://img.shields.io/codecov/c/github/thomasp85/reqres/master.svg)](https://codecov.io/github/thomasp85/reqres?branch=master)

While the http protocol is rather basic in essence, it can be a pain to work with. `reqres` is here to soothe the pain somewhat by providing two powerful classes for handling all parts of request and response handling during a http exchange. *This is not a web server*, instead it focuses on making life easier for developers of web servers by extracting the complexity of cookies, headers, content negotiation, and the likes into neat little classes. `reqres` builds upon the [`rook`](https://github.com/jeffreyhorner/Rook/blob/a5e45f751/README.md) specifications and is thus well suited for [`httpuv`-based](https://github.com/rstudio/httpuv) webservers.

Features
--------

`reqres` draws a lot of inspiration from [express.js](https://expressjs.com) and the `Request` and `Response` classes is aiming for feature parity with those from express... TBD
