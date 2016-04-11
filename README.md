# PhpStorm plugin for CakePHP

## Installation

You can install this plugin into your CakePHP application using [composer](http://getcomposer.org).

The recommended way to install composer packages is:

```
composer require skie/cakephp-php-storm
```


After install plugin run 
```
bin/cake CommandLine 
```
to generate the custom xml file for PhpStorm Command Line Tools.

File stored into .idea/commandlinetools/Custom_ck.xml 
After that you should restart PhpStorm.
After restart all shell comands should be available from command line tool (Ctrl+Shift+X) with detailed help.

## Usage example

![Sample](/docs/sample.png)