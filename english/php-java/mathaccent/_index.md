---
title: MathAccent
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/mathaccent/
---

## MathAccent class

 Specifies the accent function, consisting of a base and a combining diacritical mark
 Example: ??
 
Example:
 
```php
  $baseElement = new MathematicalText("x");
  $accent = new MathAccent($baseElement, '~');
```

## Constructors

| Name | Description |
| --- | --- |
| [MathAccent](mathaccent)(IMathElement) | Creates a math accent applying to a specified math element with the default accent character value |
| [MathAccent](mathaccent)(IMathElement, char) | Creates a math accent applying to a specified math element |

## Methods

| Name | Description |
| --- | --- |
| [getBase](getbase)() | The argument to which the accent was applied |
| [getCharacter](getcharacter)() | Accent Character The value should be within the range of (U+0300–U+036F) or(U+20D0–U+20EF) Default value: Combining Circumflex Accent (U+0302) |
| [getChildren](getchildren)() | Get children elements |
| [setCharacter](setcharacter)(char) | Accent Character The value should be within the range of (U+0300–U+036F) or(U+20D0–U+20EF) Default value: Combining Circumflex Accent (U+0302) |
