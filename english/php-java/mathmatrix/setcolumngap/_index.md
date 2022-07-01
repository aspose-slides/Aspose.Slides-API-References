---
title: setColumnGap
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 230
url: /php-java/mathmatrix/setcolumngap/
---

## setColumnGap(long value)  method

 The value of horizontal spacing between columns of a matrix;
 If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point)
 If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments.
 In other cases ignored.
 Default: 0
 
Example:
 
```php
  $matrix = new MathMatrix(2, 3);
  $matrix->setColumnGapRule(MathSpacingRules.Exactly);
  $matrix->setColumnGap(20);
```


---


