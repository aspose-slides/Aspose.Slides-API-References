---
title: MathLimit
type: docs
weight: 0
url: /php-java/mathlimit/
---

# MathLimit class

 Specifies the Limit object, consisting of text on the baseline and reduced-size text immediately above or below it.
 
Example:
 
```php
  $limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("???"));
```

## Constructors

| name | description |
| --- | --- |
| [MathLimit](/slides/php-java/mathlimit/mathlimit/)(IMathElement, IMathElement, boolean) | Initializes a new instance of the MathLimit class. |
| [MathLimit](/slides/php-java/mathlimit/mathlimit/)(IMathElement, IMathElement) | Initializes a new instance of the MathLimit class with lower limit |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getBase](/slides/php-java/mathlimit/getbase/)() | IMathElement | Base argument |
| [getChildren](/slides/php-java/mathlimit/getchildren/)() | IMathElement | Get children elements |
| [getLimit](/slides/php-java/mathlimit/getlimit/)() | IMathElement | Limit argument |
| [getUpperLimit](/slides/php-java/mathlimit/getupperlimit/)() | boolean | Specifies upper or lower limit |
| [setUpperLimit](/slides/php-java/mathlimit/setupperlimit/)(boolean) | void | Specifies upper or lower limit |
