yuml.tmbundle
=============

yuml.me TextMate Bundle with Snippets.

Snippets
--------

currently available Snippets are (all snippets are to be followed by TAB):

### Classes and Interfaces
* Interface: `interface`
* Class (simple): `class`
* Class: `class`

### Connections
* Aggregation (to-n): `connection`
* Aggregation: `connection`
* Cardinality: `connection`
* Composition: `connection`
* Dependency: `connection`
* Directional Association: `connection`
* Inheritance: `connection`
* Interface Inheritance: `connection`
* Simple Association: `connection`
* interface: `connection`


Commands
--------

* *Preview* (Command-R)

Installation
------------

### Textmate

```
git clone https://github.com/xdbr/TextMate-Bundle-yUML.git ~/Library/Application\ Support/TextMate/Bundles/yuml.tmbundle || cd $_ && git pull; cd -
```

### Sublime Text 2
```
git clone https://github.com/xdbr/TextMate-Bundle-yUML.git ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/yuml.tmbundle || cd $_ && git pull; cd -
```

The latter is reported to work for Sublime (which I haven't tried) and the first solution is the one I use for TextMate

Contributing
------------

1) `git clone` this repo regularly:

    git clone https://github.com/xdbr/TextMate-Bundle-yUML.git

2) Use TextMate's Bundle-Manager to create new snippets, etc.

3) then use `import-new-snippets-from-textmate.sh` to get the current bundle from TextMate in

4) `git commit`

Author
------

xdbr

License
-------

Beerware License

