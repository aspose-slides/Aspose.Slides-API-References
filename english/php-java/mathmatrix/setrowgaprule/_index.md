---
title: setRowGapRule
type: docs
weight: 290
url: /php-java/mathmatrix/setrowgaprule/
---

# setRowGapRule(int) method

 The type of vertical spacing between rows of a matrix; 
 Vertical spacing units can be lines or points (stored as twips).
 Default: SingleSpacingGap (0)
 
Example:
 
```php
  $matrix = new MathMatrix(2, 3);
  $matrix->setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
```

