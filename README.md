# the36review.com

This is the middleman app for the36review, found on GitHub at <https://github.com/the36review/the36review.com>.

## Setup

- Install ruby with homebrew
- cd into this directory in a terminal
- `bundle install` to install all the packages

## Development

To run it:

```sh
middleman
```

Then visit <http://localhost:4567>

## Publishing

Build the site:

```sh
rake build
```

Publish is to <http://the36review.github.io/the36review.com>:

```sh
rake publish
```
