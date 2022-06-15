---
title: MathSubscriptElement
type: docs
weight: 0
url: /php-java/mathsubscriptelement/
---

# MathSubscriptElement class

 Specifies the subscript object, which consists of a base 
 and a reduced-size subscript placed below and to the right.
 
Example:
 
```php
  $subscriptElement = new MathematicalText("N")->setSubscript("i");
```

## Constructors

| name | description |
| --- | --- |
| [MathSubscriptElement](/php-java/mathsubscriptelement/mathsubscriptelement/)(IMathElement, IMathElement) | Initializes a new instance of the MathSubscriptElement class. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getChildren](/php-java/mathsubscriptelement/getchildren/)() | IMathElement | Get children elements |
| [getSubscript](/php-java/mathsubscriptelement/getsubscript/)() | IMathElement | Subscript |
