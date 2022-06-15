---
title: getGrowToMatchOperandHeight
type: docs
weight: 100
url: /php-java/mathdelimiter/getgrowtomatchoperandheight/
---

# getGrowToMatchOperandHeight() method

 Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter
 When true, the delimiters grows vertically to match its operand height.
 The default value is true
 
Example:
 
```php
  $delimiter = new MathematicalText("x")->divide("y")->enclose();
  $delimiter->setGrowToMatchOperandHeight(false);
```


