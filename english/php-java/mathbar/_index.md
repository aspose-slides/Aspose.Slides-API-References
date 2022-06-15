---
title: MathBar
type: docs
weight: 0
url: /php-java/mathbar/
---

# MathBar class

 Specifies the bar function, consisting of a base argument and an overbar or underbar
 
Example:
 
```php
  $mathBar = new MathBar(new MathematicalText("x"));
```

## Constructors

| name | description |
| --- | --- |
| [MathBar](/slides/php-java/mathbar/mathbar/)(IMathElement) | Initializes MathBar with overbar (Top position) |
| [MathBar](/slides/php-java/mathbar/mathbar/)(IMathElement, int) | Initializes MathBar with specified position |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getBase](/slides/php-java/mathbar/getbase/)() | IMathElement | Base argument |
| [getChildren](/slides/php-java/mathbar/getchildren/)() | IMathElement | Get children elements |
| [getPosition](/slides/php-java/mathbar/getposition/)() | int | Position of the bar line. Default: Top |
| [setPosition](/slides/php-java/mathbar/setposition/)(int) | void | Position of the bar line. Default: Top |
