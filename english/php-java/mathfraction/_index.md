---
title: MathFraction
type: docs
weight: 0
url: /php-java/mathfraction/
---

# MathFraction class

 Specifies the fraction object, consisting of a numerator and denominator separated by a fraction bar.
 The fraction bar can be horizontal or diagonal, depending on the fraction properties.
 The fraction object is also used to represent the stack function, which places one element above another, with no fraction bar.
 
Example:
 
```php
  $mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes::Linear);
```

## Constructors

| name | description |
| --- | --- |
| [MathFraction](/php-java/mathfraction/mathfraction/)(IMathElement, IMathElement, int) | Initializes MathFraction with the specified numerator, denominator and type |
| [MathFraction](/php-java/mathfraction/mathfraction/)(IMathElement, IMathElement) | Initializes a MathFraction of type 'Bar' with the specified numerator and denominator |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getChildren](/php-java/mathfraction/getchildren/)() | IMathElement | Get children elements |
| [getDenominator](/php-java/mathfraction/getdenominator/)() | IMathElement | Denominator |
| [getFractionType](/php-java/mathfraction/getfractiontype/)() | int | Fraction type Default: Bar |
| [getNumerator](/php-java/mathfraction/getnumerator/)() | IMathElement | Numerator |
| [setFractionType](/php-java/mathfraction/setfractiontype/)(int) | void | Fraction type Default: Bar |
