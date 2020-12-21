wronghanded
===========

adding privlegedz

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/wronghanded.svg)](https://npmjs.org/package/wronghanded)
[![Downloads/week](https://img.shields.io/npm/dw/wronghanded.svg)](https://npmjs.org/package/wronghanded)
[![License](https://img.shields.io/npm/l/wronghanded.svg)](https://github.com/home/wronghanded/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g wronghanded
$ cmndr COMMAND
running command...
$ cmndr (-v|--version|version)
wronghanded/1.0.0 linux-x64 node-v10.19.0
$ cmndr --help [COMMAND]
USAGE
  $ cmndr COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`cmndr hello [FILE]`](#cmndr-hello-file)
* [`cmndr help [COMMAND]`](#cmndr-help-command)

## `cmndr hello [FILE]`

describe the command here

```
USAGE
  $ cmndr hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ cmndr hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/home/wronghanded/blob/v1.0.0/src/commands/hello.ts)_

## `cmndr help [COMMAND]`

display help for cmndr

```
USAGE
  $ cmndr help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.1/src/commands/help.ts)_
<!-- commandsstop -->
