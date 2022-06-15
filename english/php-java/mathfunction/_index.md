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
| [MathFunction](/php-java/mathfunction/mathfunction/)(IMathElement, IMathElement) | Initializes a new instance of the MathFunction class. |
| [MathFunction](/php-java/mathfunction/mathfunction/)(String, IMathElement) | Initializes a new instance of the MathFunction class. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getBase](/php-java/mathfunction/getbase/)() | IMathElement | Function Argument |
| [getChildren](/php-java/mathfunction/getchildren/)() | IMathElement | Get children elements |
| [getName](/php-java/mathfunction/getname/)() | IMathElement | Function name For example, function names are sin and cos |
