noddle
======

Simple way to open a Node.js REPL with your currnet workspace included.

### Setup

`noddle` is on `npm`, so go ahead and install it globally:

```bash
$ npm install -g noddle
```

### Usage

Super easy to use via a command line:

```bash
$ noddle <name>
```

The "name" option is the variable name the current workspace should be loaded under. If one is not provided, it will load using the module name provided in the `package.json` (but with hyphens replaced with underscores).
