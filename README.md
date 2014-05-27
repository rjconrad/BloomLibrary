A web site for sharing literacy materials, especially templates for translation into minority languages.

***

## Quick Start

Make sure you have [Nodejs](http://nodejs.org/download/) and then:

```sh
git clone  https://github.com/BloomBooks/BloomLibrary.git
cd BloomLibrary
sudo npm -g install grunt-cli karma bower  (on Linux)
npm -g install grunt-cli karma bower     ( on Windows)
npm install
bower install
grunt watch
```

(Currently bower asks you to choose between several versions of angular js,
you should choose 1.0.8 which is typically choice 1.
Also between versions of jquery...choose 2.0.3.
Some specific versions are required because source files that our program
references change locations or the name includes the version.)

Finally, open `file:///path/to/bloomlibrary/build/index.html` in your browser.

After pulling new releases, you may need to update various libraries. Do that with


```sh
npm update
bower update
```

## About the grunt files

We built these using [ngBoilerplate](https://github.com/ngbp/ngbp). See the readme of ngBoilerplate for more information about the directory structure and the purpose of many files.

## Roadmap

see https://trello.com/b/eO6j48sf/bloom-library

### Contributing

Books may be contributed to the website once we have it working. Code contributions are welcome also.
We recommend interactin through the Trello board to be sure we're on the same track.

Copyright and License
=======
Copyright 2013-2014 [SIL International](http://sil.org)
[MIT/X11](http://sil.mit-license.org/)


