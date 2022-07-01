---
title: remove
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 230
url: /php-java/mathblock/remove/
---

## remove(BaseScript item)  method
## remove(MathAccent item)  method
## remove(MathArray item)  method
## remove(MathBar item)  method
## remove(MathBlock item)  method
## remove(MathBorderBox item)  method
## remove(MathBox item)  method
## remove(MathDelimiter item)  method
## remove(MathElementBase item)  method
## remove(MathematicalText item)  method
## remove(MathFraction item)  method
## remove(MathFunction item)  method
## remove(MathGroupingCharacter item)  method
## remove(MathLeftSubSuperscriptElement item)  method
## remove(MathLimit item)  method
## remove(MathMatrix item)  method
## remove(MathNaryOperator item)  method
## remove(MathRadical item)  method
## remove(MathRightSubSuperscriptElement item)  method
## remove(MathSubscriptElement item)  method
## remove(MathSuperscriptElement item)  method

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


