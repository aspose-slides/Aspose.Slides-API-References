---
title: MathGroupingCharacter
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/mathgroupingcharacter/
---

## MathGroupingCharacter class

 Specifies a grouping symbol above or below an expression, usually to highlight the relationship between elements 
 
Example:
 
```php
  $groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
```

## Constructors

| Name | Description |
| --- | --- |
| [MathGroupingCharacter](mathgroupingcharacter)(IMathElement) | Initializes a new instance of the MathGroupingCharacter class with the default grouping character U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter](mathgroupingcharacter)(IMathElement, char, int, int) | Initializes a new instance of the MathGroupingCharacter class. |

## Methods

| Name | Description |
| --- | --- |
| [getBase](getbase)() | Base argument |
| [getCharacter](getcharacter)() | Grouping Character Default value: U+23DF (BOTTOM CURLY BRACKET) |
| [getChildren](getchildren)() | Get children elements |
| [getPosition](getposition)() | Position of grouping character. Default: Bottom |
| [getVerticalJustification](getverticaljustification)() | Vertical justification of group character. Specifies the alignment of the object with respect to the baseline. For example, when the group character is above the object, VerticalJustification of Top signifies that the top of the object falls on the baseline; when VerticalJustification is set to Bottom, the bottom of the object is on the baseline Default: Bottom for Position=Top, and Top for Position=Bottom |
| [setCharacter](setcharacter)(char) | Grouping Character Default value: U+23DF (BOTTOM CURLY BRACKET) |
| [setPosition](setposition)(int) | Position of grouping character. Default: Bottom |
| [setVerticalJustification](setverticaljustification)(int) | Vertical justification of group character. Specifies the alignment of the object with respect to the baseline. For example, when the group character is above the object, VerticalJustification of Top signifies that the top of the object falls on the baseline; when VerticalJustification is set to Bottom, the bottom of the object is on the baseline Default: Bottom for Position=Top, and Top for Position=Bottom |
