python
========

A style guide to python 3

By Sean Westfall

## Table of Contents
  1. [Official Documentation](#official-documentation)
  1. [Virtual Environments](#virtual-environments)
  1. [Pip](#pip)
  1. [Properties](#properties)
  1. [Syntax](#syntax)
  1. [Data Types](#data-types)
  1. [Strings](#strings)
  1. [Flow Control Statements](#flow-control-statements)
  1. [Functions](#functions)
  1. [Classes](#classes)
  1. [Exceptions](#exceptions)
  1. [Importing](#importing)
  1. [Asyncio](#asyncio)
  1. [File I/O](#file-i/0)
  1. [Design Patterns](#design-patterns)
  1. [Logging](#logging)
  1. [License](#license)

## Official Documentation
[Python Documentation](https://docs.python.org/3.8/tutorial/)

Provides a guide to all versions of Python (2.7..3.8) including the current developmental branch (as of now 3.9).

**[⬆ back to top](#table-of-contents)**

## Virtual Environments

To create a new virtual environment (`/path/to/new/virtual/environment` is the directory of your project):

```
$ python3 -m venv /path/to/new/virtual/environment
```

then to activate (where `project-name` is the name of your project):

```
$ source project-name/bin/activate
```

**[⬆ back to top](#table-of-contents)**

## Pip

Dependencies in a requirement.txt file can be installed this way:

```
$ python3 -m pip install -r requirements.txt
```

**[⬆ back to top](#table-of-contents)**

## Properties

**[⬆ back to top](#table-of-contents)**

## Syntax

**[⬆ back to top](#table-of-contents)**

## Data Types

**[⬆ back to top](#table-of-contents)**

## Strings

**[⬆ back to top](#table-of-contents)**

## Flow Control Statements

**[⬆ back to top](#table-of-contents)**

## Functions

**[⬆ back to top](#table-of-contents)**

## Classes

Basic syntax   

```python
class ClassName:
    .
    .
    .
```

Classes my have a constructor, used with the keyword `__init__`
```python
def __init__(self):
    self.data = []
```

**[⬆ back to top](#table-of-contents)**

## Exceptions

**[⬆ back to top](#table-of-contents)**

## Importing

**[⬆ back to top](#table-of-contents)**

## Asyncio

(Async Lib)[https://docs.python.org/3/library/asyncio.html]  

asyncio is a library to write concurrent code using the async/await syntax.  

**[⬆ back to top](#table-of-contents)**

## File I/O

**[⬆ back to top](#table-of-contents)**

## Logging

**[⬆ back to top](#table-of-contents)**

## License

(The MIT License)

Copyright (c) 2020 Sean Westfall

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

**[⬆ back to top](#table-of-contents)**
