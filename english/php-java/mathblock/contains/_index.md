---
title: contains
type: docs
weight: 60
url: /php-java/mathblock/contains/
---

# contains(com.aspose.slides.IMathElement) method

 Determines whether the collection contains a specific value.
 
Example:
 
```php
  $mathBlock = new MathBlock(new MathematicalText("x"));
  $plusElement = new MathematicalText("+");
  $mathBlock->Add($plusElement);
  $mathBlock->Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
  $contains = $mathBlock->Contains($plusElement);
```

##  Parameters

| name | description |
| --- | --- |
| item | The object to locate in the collection. |

##  Returns
true if item is found in the collection; otherwise, false.


