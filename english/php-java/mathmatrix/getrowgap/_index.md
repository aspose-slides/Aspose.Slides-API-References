---
title: getRowGap
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 140
url: /php-java/mathmatrix/getrowgap/
---

## getRowGap()  method

 The value of vertical spacing between rows of a matrix;
 If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point)
 If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines.
 Default: 0
 
Example:
 
```php
  $matrix = new MathMatrix(2, 3);
  $matrix->setRowGapRule(MathSpacingRules.Exactly);
  $matrix->setRowGap(20);
```

### Returns
long


---


