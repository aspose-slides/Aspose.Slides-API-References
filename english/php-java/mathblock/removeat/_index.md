---
title: removeAt
type: docs
weight: 240
url: /php-java/mathblock/removeat/
---

# removeAt(int) method

 Removes the element at the specified index of the collection.
 
Example:
 
```php
  $mathBlock = new MathBlock(new MathematicalText("x"));
  $plusElement = new MathematicalText("+");
  $mathBlock->add($plusElement);
  $mathBlock->insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
  $mathBlock->removeAt(2);
```

##  Parameters

| name | description |
| --- | --- |
| index | The zero-based index of the element to remove. |


