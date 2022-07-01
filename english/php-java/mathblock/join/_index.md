---
title: join
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 200
url: /php-java/mathblock/join/
---

## join(BaseScript mathElement)  method
## join(MathAccent mathElement)  method
## join(MathArray mathElement)  method
## join(MathBar mathElement)  method
## join(MathBlock mathElement)  method
## join(MathBorderBox mathElement)  method
## join(MathBox mathElement)  method
## join(MathDelimiter mathElement)  method
## join(MathElementBase mathElement)  method
## join(MathematicalText mathElement)  method
## join(MathFraction mathElement)  method
## join(MathFunction mathElement)  method
## join(MathGroupingCharacter mathElement)  method
## join(MathLeftSubSuperscriptElement mathElement)  method
## join(MathLimit mathElement)  method
## join(MathMatrix mathElement)  method
## join(MathNaryOperator mathElement)  method
## join(MathRadical mathElement)  method
## join(MathRightSubSuperscriptElement mathElement)  method
## join(MathSubscriptElement mathElement)  method
## join(MathSuperscriptElement mathElement)  method

 Joins a mathematical element with this mathematical block
 
Example:
 
```php
  $element1 = new MathematicalText("x");
  $element2 = new MathematicalText("y");
  $block = $element1->join($element2);
```

### Parameters

| Name | Description |
| --- | --- |
| mathElement | The element to be joined |

### Returns
The current instance of IMathBlock


---


## join(String mathText)  method

 Joins a mathematical text with this mathematical block
 
Example:
 
```php
  $element = new MathematicalText("x");
  $block = $element->join("+y");
```

### Parameters

| Name | Description |
| --- | --- |
| mathText | Mathematical text to be joined |

### Returns
A new IMathBlock containing this instance and specified argument


---


