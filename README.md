linter-csslint
=========================

This linter plugin for [Linter](https://github.com/AtomLinter/Linter) provides an interface to [csslint](https://github.com/CSSLint/csslint). It will be used with files that have the “CSS” or “HTML” syntax.

## Installation
Linter package must be installed in order to use this plugin. If Linter is not installed, please follow the instructions [here](https://github.com/AtomLinter/Linter).

### Plugin installation
```
$ apm install linter-csslint
```

## Settings
You can configure linter-csslint by editing ~/.atom/config.cson (choose Open Your Config in Atom menu):
```
'linter-csslint':
  'csslintExecutablePath': null #csslint path. run 'which csslint' to find the path
```

## Contributing
If you would like to contribute enhancements or fixes, please do the following:

1. Fork the plugin repository.
1. Hack on a separate topic branch created from the latest `master`.
1. Commit and push the topic branch.
1. Make a pull request.
1. welcome to the club

Please note that modications should follow these coding guidelines:

- Indent is 2 spaces.
- Code should pass coffeelint linter.
- Vertical whitespace helps readability, don’t be afraid to use it.

Thank you for helping out!
