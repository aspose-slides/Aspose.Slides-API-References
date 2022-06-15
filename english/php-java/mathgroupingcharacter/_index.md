---
title: MathGroupingCharacter
type: docs
weight: 0
url: /php-java/mathgroupingcharacter/
---

# MathGroupingCharacter class

 Specifies a grouping symbol above or below an expression, usually to highlight the relationship between elements 
 
Example:
 
```php
  $groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
```

## Constructors

| name | description |
| --- | --- |
| [MathGroupingCharacter](/php-java/mathgroupingcharacter/mathgroupingcharacter/)(IMathElement) | Initializes a new instance of the MathGroupingCharacter class with the default grouping character U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter](/php-java/mathgroupingcharacter/mathgroupingcharacter/)(IMathElement, char, int, int) | Initializes a new instance of the MathGroupingCharacter class. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getBase](/php-java/mathgroupingcharacter/getbase/)() | IMathElement | Base argument |
| [getCharacter](/php-java/mathgroupingcharacter/getcharacter/)() | char | Grouping Character Default value: U+23DF (BOTTOM CURLY BRACKET) |
| [getChildren](/php-java/mathgroupingcharacter/getchildren/)() | IMathElement | Get children elements |
| [getPosition](/php-java/mathgroupingcharacter/getposition/)() | int | Position of grouping character. Default: Bottom |
| [getVerticalJustification](/php-java/mathgroupingcharacter/getverticaljustification/)() | int | Vertical justification of group character. Specifies the alignment of the object with respect to the baseline. For example, when the group character is above the object, VerticalJustification of Top signifies that the top of the object falls on the baseline; when VerticalJustification is set to Bottom, the bottom of the object is on the baseline Default: Bottom for Position=Top, and Top for Position=Bottom |
| [setCharacter](/php-java/mathgroupingcharacter/setcharacter/)(char) | void | Grouping Character Default value: U+23DF (BOTTOM CURLY BRACKET) |
| [setPosition](/php-java/mathgroupingcharacter/setposition/)(int) | void | Position of grouping character. Default: Bottom |
| [setVerticalJustification](/php-java/mathgroupingcharacter/setverticaljustification/)(int) | void | Vertical justification of group character. Specifies the alignment of the object with respect to the baseline. For example, when the group character is above the object, VerticalJustification of Top signifies that the top of the object falls on the baseline; when VerticalJustification is set to Bottom, the bottom of the object is on the baseline Default: Bottom for Position=Top, and Top for Position=Bottom |
