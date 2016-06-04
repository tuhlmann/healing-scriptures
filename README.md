# healing-scriptures
Sid Roth's 'The Healing Scriptures' translated into German

The book is processed using `AsciiDoctor`.

Currently we use the toolchain found at: https://github.com/chloerei/asciidoctor-book-template

## Installing the toolchain

### Linux

- `sudo apt-get install build-essential bundler libz-dev libxslt-dev libxml2-dev`
- `bundle install` (inside the repository directory)

Use `bundle update` to update the toolchain.

## Building the book

`bundle exec rake` will build the book.
