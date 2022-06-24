---
title: MathLeftSubSuperscriptElement
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/mathleftsubsuperscriptelement/
---

## MathLeftSubSuperscriptElement class

 Specifies the Sub-Superscript object, which consists of a base 
 and a subscript and superscript placed to the left of the base.
 
Example:
 
```php
  $baseElement = new MathematicalText("X");
  $subscript = new MathematicalText("i");
  $superscript = new MathematicalText("j");
  $leftSubSuperscript = new MathLeftSubSuperscriptElement($baseElement, $subscript, $superscript);
```

## Constructors

| Name | Description |
| --- | --- |
| [MathLeftSubSuperscriptElement](mathleftsubsuperscriptelement)(IMathElement, IMathElement, IMathElement) | Initializes a new instance of the MathLeftSubSuperscriptElement class. |

## Methods

| Name | Description |
| --- | --- |
| [getChildren](getchildren)() | Get children elements |
| [getSubscript](getsubscript)() | Subscript |
| [getSuperscript](getsuperscript)() | Superscript |
