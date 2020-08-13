# Emilia

An virtual environment for global package.

# Add pacakges

```
$ cd global/
$ npm install <package> # Javascript npm
$ echo 'gem "<package>"' >> Gemfile # Ruby gem
$ pipenv install <package> # Python pip
```

# Rebuild environment

```
$ cd global/
$ npm install
$ bundle install
$ pipenv install
```

# Use environment

```
PATH=emilia/node_modules/.bin:$PATH
```

Python and Ruby binary can't be run directly.
