---
title: getVerticalJustification
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 80
url: /php-java/mathgroupingcharacter/getverticaljustification/
---

## getVerticalJustification()  method

 Vertical justification of group character.
 Specifies the alignment of the object with respect to the baseline.
 For example, when the group character is above the object, 
 VerticalJustification of Top signifies that the top of the object falls on the baseline;
 when VerticalJustification is set to Bottom, the bottom of the object is on the baseline
 Default: Bottom for Position=Top, and Top for Position=Bottom
 
Example:
 
```php
  $groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
  $groupingCharacter->setVerticalJustification(MathTopBotPositions.Top);
```


---


