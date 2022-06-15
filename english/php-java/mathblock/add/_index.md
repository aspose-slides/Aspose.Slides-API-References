---
title: add
type: docs
weight: 40
url: /php-java/mathblock/add/
---

# add(com.aspose.slides.IMathElement) method

 Adds a math element to the end of the collection.
 
Example:
 
```php
  $mathBlock = new MathBlock(new MathematicalText("x"));
  $mathBlock->add(new MathematicalText("+"));
  $mathBlock->add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
```

##  Parameters

| name | description |
| --- | --- |
| item | The IMathElement to be added to the end of the collection. |


