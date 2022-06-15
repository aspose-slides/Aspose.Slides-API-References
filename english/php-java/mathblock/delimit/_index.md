---
title: delimit
type: docs
weight: 80
url: /php-java/mathblock/delimit/
---

# delimit(char) method

 Delimits child elements with separator character (without the brackets)
 
Example:
 
```php
  $mathBlock = new MathematicalText("x")->join("y");
  $delimiterElement = $mathBlock->delimit('|');
```

##  Parameters

| name | description |
| --- | --- |
| separatorCharacter | Separator character |

##  Returns
The math element of type IMathDelimiter


