---
title: MathAccent
type: docs
weight: 0
url: /php-java/mathaccent/
---

# MathAccent class

 Specifies the accent function, consisting of a base and a combining diacritical mark
 Example: ??
 
Example:
 
```php
  $baseElement = new MathematicalText("x");
  $accent = new MathAccent($baseElement, '~');
```

## Constructors

| name | description |
| --- | --- |
| [MathAccent](/php-java/mathaccent/mathaccent/)(IMathElement) | Creates a math accent applying to a specified math element with the default accent character value |
| [MathAccent](/php-java/mathaccent/mathaccent/)(IMathElement, char) | Creates a math accent applying to a specified math element |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getBase](/php-java/mathaccent/getbase/)() | IMathElement | The argument to which the accent was applied |
| [getCharacter](/php-java/mathaccent/getcharacter/)() | char | Accent Character The value should be within the range of (U+0300–U+036F) or(U+20D0–U+20EF) Default value: Combining Circumflex Accent (U+0302) |
| [getChildren](/php-java/mathaccent/getchildren/)() | IMathElement | Get children elements |
| [setCharacter](/php-java/mathaccent/setcharacter/)(char) | void | Accent Character The value should be within the range of (U+0300–U+036F) or(U+20D0–U+20EF) Default value: Combining Circumflex Accent (U+0302) |
