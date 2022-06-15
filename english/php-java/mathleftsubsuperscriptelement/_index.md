---
title: MathLeftSubSuperscriptElement
type: docs
weight: 0
url: /php-java/mathleftsubsuperscriptelement/
---

# MathLeftSubSuperscriptElement class

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

| name | description |
| --- | --- |
| [MathLeftSubSuperscriptElement](/php-java/mathleftsubsuperscriptelement/mathleftsubsuperscriptelement/)(IMathElement, IMathElement, IMathElement) | Initializes a new instance of the MathLeftSubSuperscriptElement class. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getChildren](/php-java/mathleftsubsuperscriptelement/getchildren/)() | IMathElement | Get children elements |
| [getSubscript](/php-java/mathleftsubsuperscriptelement/getsubscript/)() | IMathElement | Subscript |
| [getSuperscript](/php-java/mathleftsubsuperscriptelement/getsuperscript/)() | IMathElement | Superscript |
