---
title: setDelimiterShape
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 150
url: /php-java/mathdelimiter/setdelimitershape/
---

## setDelimiterShape(int value)  method

 Specifies the shape of delimiters in the delimiter object. 
 When is MathDelimiterShape.Centered, delimiters are centered around the math axis of the mathematical text 
 and still be made to fit the entire height of their contents.
 When is MathDelimiterShape.Match, their height and shape are altered to exactly match their contents.
 
Example:
 
```php
  $delimiter = new MathematicalText("x")->divide("y")->enclose();
  $delimiter->setDelimiterShape(MathDelimiterShape.Match);
```

### Returns
void


---


