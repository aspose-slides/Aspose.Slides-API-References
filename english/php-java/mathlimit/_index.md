---
title: MathLimit
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/mathlimit/
---

## MathLimit class

 Specifies the Limit object, consisting of text on the baseline and reduced-size text immediately above or below it.
 
Example:
 
```php
  $limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("???"));
```

## Constructors

| Name | Description |
| --- | --- |
| [MathLimit](mathlimit)(IMathElement, IMathElement, boolean) | Initializes a new instance of the MathLimit class. |
| [MathLimit](mathlimit)(IMathElement, IMathElement) | Initializes a new instance of the MathLimit class with lower limit |

## Methods

| Name | Description |
| --- | --- |
| [getBase](getbase)() | Base argument |
| [getChildren](getchildren)() | Get children elements |
| [getLimit](getlimit)() | Limit argument |
| [getUpperLimit](getupperlimit)() | Specifies upper or lower limit |
| [setUpperLimit](setupperlimit)(boolean) | Specifies upper or lower limit |
