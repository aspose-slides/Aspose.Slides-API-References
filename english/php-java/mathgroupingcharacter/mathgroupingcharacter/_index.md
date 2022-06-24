---
title: MathGroupingCharacter
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/mathgroupingcharacter/mathgroupingcharacter/
---

## MathGroupingCharacter(com.aspose.slides.IMathElement) constructor

Initializes a new instance of the MathGroupingCharacter class with the default grouping character U+23DF (BOTTOM CURLY BRACKET)
Example:
 
```php
  $groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
```

### Parameters

| Parameter |Description |
| --- | --- |
| element | The base element to which the bar is applied |
 

---


## MathGroupingCharacter(com.aspose.slides.IMathElement, char, int, int) constructor

Initializes a new instance of the MathGroupingCharacter class.
Example:
 
```php
  $groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

### Parameters

| Parameter |Description |
| --- | --- |
| element | The base element to which the bar is applied |
| character | Grouping Character |
| position | Position of grouping character |
| verticalJustification | Vertical justification of group character |
 

---


