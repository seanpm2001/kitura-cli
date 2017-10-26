# Kitura command-line interface

This Node.js package provides a `kitura` command-line interface, to simplify the process of creating [Kitura](https://github.com/IBM-Swift/Kitura) applications.

## Installation via Homebrew

```
$ brew tap ibm-swift/kitura
$ brew install kitura
```

## Installation via NPM

```
$ npm install -g yo
$ npm install -g generator-swiftserver
$ npm install -g kitura-cli
```

## Usage

```
$ kitura

  Usage: kitura [options] [command]

  Kitura command-line interface


  Options:

    -V, --version  output the version number
    -h, --help     output usage information


  Commands:

    build       build the project in a local container
    create      interactively create a Kitura project
    idt         install IBM Cloud Developer Tools
    init        scaffold a bare-bones Kitura project
    kit         download the KituraKit zip file
    run         run the project in a local container
    help [cmd]  display help for [cmd]
```
