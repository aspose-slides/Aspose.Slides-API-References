---
title: setExplicitBreak
type: docs
weight: 120
url: /php-java/mathbox/setexplicitbreak/
---

# setExplicitBreak(byte) method

 Explicit break specifies whether there is a line break at the start of the Box object, 
 such that the line wraps at the start of the box object.
 Specifies the number of the operator on the previous line of mathematical text which shall
 be used as the alignment point for the current line of mathematical text
 possible values: 1..255
 Default: 0 (no explicit break)
 
Example:
 
```php
  $box = new MathematicalText("==")->toBox();
  $box->setExplicitBreak(1);
```

