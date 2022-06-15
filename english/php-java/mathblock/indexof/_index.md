---
title: indexOf
type: docs
weight: 150
url: /php-java/mathblock/indexof/
---

# indexOf(com.aspose.slides.IMathElement) method

 Determines the index of a specific math element in collection.
 
Example:
 
```php
  $mathBlock = new MathBlock(new MathematicalText("x"));
  $plusElement = new MathematicalText("+");
  $mathBlock->add($plusElement);
  $mathBlock->add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
  $index = $mathBlock->indexOf($plusElement);
```

##  Parameters

| name | description |
| --- | --- |
| item | The element to locate in the collection. |

##  Returns
The index of item if found in the collection; otherwise, -1.


