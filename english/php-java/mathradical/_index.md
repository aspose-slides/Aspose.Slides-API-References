---
title: MathRadical
type: docs
weight: 0
url: /php-java/mathradical/
---

# MathRadical class

 Specifies the radical function, consisting of a base, and an optional degree.
 Example of radical object is ??.
 
Example:
 
```php
  $radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
```

## Constructors

| name | description |
| --- | --- |
| [MathRadical](/php-java/mathradical/mathradical/)(IMathElement, IMathElement) | Initializes a new instance of the MathRadical class. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getBase](/php-java/mathradical/getbase/)() | IMathElement | Base argument |
| [getChildren](/php-java/mathradical/getchildren/)() | IMathElement | Get children elements |
| [getDegree](/php-java/mathradical/getdegree/)() | IMathElement | Degree argument |
| [getHideDegree](/php-java/mathradical/gethidedegree/)() | boolean | Hide degree When is true, the degree is not shown, as in ?? |
| [setHideDegree](/php-java/mathradical/sethidedegree/)(boolean) | void | Hide degree When is true, the degree is not shown, as in ?? |
