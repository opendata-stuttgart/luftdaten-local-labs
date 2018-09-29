# Luftdaten-local-labs

These are the source files for the map of local Luftdaten.info labs and contacts.

## Setup

You first need to install git Ruby and gem.

Then get the dependencies:
```
gem install bundler
bundler install
```

You can now build and serve the site:
```
bundler exec jekyll serve
```

## Add new lab

Go to the folder _labs, create a copy of stuttgart.yml. Rename it (name of city as filename prefered) and make your changes.
