---
title: getRowSpacing
type: docs
weight: 80
url: /php-java/matharray/getrowspacing/
---

# getRowSpacing() method

 Spacing between rows of an array
 It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points 
 or Multiple in which case the unit of measure is half-lines.
 Default: 0
 
Example:
 
```php
  $mathArray = new MathArray(new MathematicalText("item1"));
  $mathArray->setRowSpacingRule(MathRowSpacingRule.Exactly);
  $mathArray->setRowSpacing(10);
```


