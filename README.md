# Vagrantfiles (NPM)

## Dependencies
- Vagrant

## Installation

##### Global Installation
```
npm install -g vagrantfiles
```

##### Local Installation
```
npm install --save vagrantfiles
```

## Usage

##### Global Usage (First Navigate to Desired Directory)
```sh
vagrantfiles node
```

##### Local Usage
```js
var vagrantfiles = require('vagrantfiles');
vagrantfiles.create("node", function(err, success){
  if(err) throw err;
  if(success){
    console.log(success); 
  }
});
```

## ISC License (ISC)

Copyright (c) 4-digit year, Company or Person's Name <E-mail address>

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.