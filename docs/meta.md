# Documentation


*WECS* documentation is made of two sources:
- a set of .md files residing in the `/manual/` folder, describing the system. and
- the docstrings in the code that generate the API Reference section

The .md files are translated to .rst files and than uploaded to https://wecs.readthedocs.io/

## Generating

To generate docs you should simply run `./gen.sh` from the /doc directory.
This generates the needed files and the resulting html.

### Requirements

You'll need the `pandoc` conversion utility to be installed.
