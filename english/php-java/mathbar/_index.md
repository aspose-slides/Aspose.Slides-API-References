---
title: MathBar
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/mathbar/
---

## MathBar class

 Specifies the bar function, consisting of a base argument and an overbar or underbar
 
Example:
 
```php
  $mathBar = new MathBar(new MathematicalText("x"));
```

## Constructors

| Name | Description |
| --- | --- |
| [MathBar](mathbar)(IMathElement) | Initializes MathBar with overbar (Top position) |
| [MathBar](mathbar)(IMathElement, int) | Initializes MathBar with specified position |

## Methods

| Name | Description |
| --- | --- |
| [getBase](getbase)() | Base argument |
| [getChildren](getchildren)() | Get children elements |
| [getPosition](getposition)() | Position of the bar line. Default: Top |
| [setPosition](setposition)(int) | Position of the bar line. Default: Top |
