# Overview

This is a template to quickly spin up a Pipenv Python environment. Primarily for
quickly putting together scripts that require some dependencies, such as 
`Requests`, within a virutal environment.

Once set up, you can modify `app.py` (and just write Python code in general), to
get things going!

You'll quickly see that it isn't too hard to set up something like this without this repository. 
So I guess this is more of a brief tutorial, or a quick reminder, for those who use Python
for infrequent ad-hoc scripting.

# Set up

Make sure you have the following dependencies installed:
* `python`
* `pip`
* `pipenv`
Google is your friend, should you need to install dependencies.

To create and enable the virtual environment:
```
pipenv shell
```

And to run your script:
```
python app.py
```

# Quick tips

## Commands for the lazy

### Add a new library

```
pipenv install <library name>
```

### Import script into an interactive shell

If you'd like to do everything interactively, rather than through a script, but still create functions to import from `app.py`:

```
pipenv shell
python
from app import *
run()
```

## Useful libraries for scripting

* [Requests](https://docs.python-requests.org/en/master/) - [PyPi project](https://pypi.org/project/requests/)
* [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/) - [PyPi project](https://pypi.org/project/beautifulsoup4/)
* [lxml](https://lxml.de/) - [PyPi project](https://pypi.org/project/lxml/)
* [sh](https://amoffat.github.io/sh) - [PyPi project](https://pypi.org/project/sh/)
