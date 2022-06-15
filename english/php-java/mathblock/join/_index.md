---
title: join
type: docs
weight: 200
url: /php-java/mathblock/join/
---

# join(com.aspose.slides.IMathElement) method

 Joins a mathematical element with this mathematical block
 
Example:
 
```php
  $element1 = new MathematicalText("x");
  $element2 = new MathematicalText("y");
  $block = $element1->join($element2);
```

##  Parameters

| name | description |
| --- | --- |
| mathElement | The element to be joined |

##  Returns
The current instance of IMathBlock


# join(java.lang.String) method

 Joins a mathematical text with this mathematical block
 
Example:
 
```php
  $element = new MathematicalText("x");
  $block = $element->join("+y");
```

##  Parameters

| name | description |
| --- | --- |
| mathText | Mathematical text to be joined |

##  Returns
A new IMathBlock containing this instance and specified argument


