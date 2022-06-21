---
title: remove
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 230
url: /php-java/mathblock/remove/
---

## remove(com.aspose.slides.IMathElement) method

 Removes the first occurrence of a specific object from the collection.
 
Example:
 
```php
  $mathBlock = new MathBlock(new MathematicalText("x"));
  $plusElement = new MathematicalText("+");
  $mathBlock->Add($plusElement);
  $mathBlock->Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
  $mathBlock->Remove($plusElement);
```

### Parameters

| Name | Description |
| --- | --- |
| item | The object to remove from the collection. |

### Returns
true if item was successfully removed from the collection; otherwise, false. This method also returns false if item is not found in the original collection.


---


