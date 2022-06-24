---
title: MathFraction
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/mathfraction/
---

## MathFraction class

 Specifies the fraction object, consisting of a numerator and denominator separated by a fraction bar.
 The fraction bar can be horizontal or diagonal, depending on the fraction properties.
 The fraction object is also used to represent the stack function, which places one element above another, with no fraction bar.
 
Example:
 
```php
  $mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes::Linear);
```

## Constructors

| Name | Description |
| --- | --- |
| [MathFraction](mathfraction)(IMathElement, IMathElement, int) | Initializes MathFraction with the specified numerator, denominator and type |
| [MathFraction](mathfraction)(IMathElement, IMathElement) | Initializes a MathFraction of type 'Bar' with the specified numerator and denominator |

## Methods

| Name | Description |
| --- | --- |
| [getChildren](getchildren)() | Get children elements |
| [getDenominator](getdenominator)() | Denominator |
| [getFractionType](getfractiontype)() | Fraction type Default: Bar |
| [getNumerator](getnumerator)() | Numerator |
| [setFractionType](setfractiontype)(int) | Fraction type Default: Bar |
