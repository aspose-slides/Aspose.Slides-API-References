---
title: setColumnGapRule
type: docs
weight: 240
url: /php-java/mathmatrix/setcolumngaprule/
---

# setColumnGapRule(int) method

 The type of horizontal spacing between columns of a matrix; 
 Horizontal spacing units can be ems or points (stored as twips).
 Default: SingleSpacingGap (0)
 
Example:
 
```php
  $matrix = new MathMatrix(2, 3);
  $matrix->setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
```

