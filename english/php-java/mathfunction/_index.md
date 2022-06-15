---
title: MathFunction
type: docs
weight: 0
url: /php-java/mathfunction/
---

# MathFunction class

 Specifies a function of an argument.
 
Example:
 
```php
  $func = new MathFunction("sin", new MathematicalText("x"));
```

## Constructors

| name | description |
| --- | --- |
| [MathFunction](/slides/php-java/mathfunction/mathfunction/)(IMathElement, IMathElement) | Initializes a new instance of the MathFunction class. |
| [MathFunction](/slides/php-java/mathfunction/mathfunction/)(String, IMathElement) | Initializes a new instance of the MathFunction class. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getBase](/slides/php-java/mathfunction/getbase/)() | IMathElement | Function Argument |
| [getChildren](/slides/php-java/mathfunction/getchildren/)() | IMathElement | Get children elements |
| [getName](/slides/php-java/mathfunction/getname/)() | IMathElement | Function name For example, function names are sin and cos |
