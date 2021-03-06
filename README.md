# Github-search [![Build Status](https://secure.travis-ci.org/noblesamurai/github-search.png?branch=master)](http://travis-ci.org/noblesamurai/github-search) [![NPM version](https://badge-me.herokuapp.com/api/npm/github-search.png)](http://badges.enytc.com/for/npm/github-search)

> Search github for issues/PRs using the github API, formatted as simple tabular output.

## Purpose
Print github search of issues/PRs to a tab separated simple text output.

## Usage

### Find Issues

``` bash
node index.js --token MYTOKEN 'is:pr org:myorg created:2017-07-01..2018-07-01 sort:created-asc'
```

### Find Commits

``` bash
node index.js --commits --token MYTOKEN 'committer-date:2017-07-01..2018-07-01 sort:commiter-date-asc repo:myorg/myrepo'
```


## Installation

This module is installed via npm:

``` bash
$ npm install -g github-search-repos-to-simple-text
```
## License

The BSD License

Copyright (c) 2017, Tim Allen

All rights reserved.

Redistribution and use in source and binary forms, with or without modification,
are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice, this
  list of conditions and the following disclaimer in the documentation and/or
  other materials provided with the distribution.

* Neither the name of the Tim Allen nor the names of its
  contributors may be used to endorse or promote products derived from
  this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR
ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON
ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

