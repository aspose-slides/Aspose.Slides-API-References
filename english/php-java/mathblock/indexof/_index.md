---
title: indexOf
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 150
url: /php-java/mathblock/indexof/
---

## indexOf(BaseScript item)  method
## indexOf(MathAccent item)  method
## indexOf(MathArray item)  method
## indexOf(MathBar item)  method
## indexOf(MathBlock item)  method
## indexOf(MathBorderBox item)  method
## indexOf(MathBox item)  method
## indexOf(MathDelimiter item)  method
## indexOf(MathElementBase item)  method
## indexOf(MathematicalText item)  method
## indexOf(MathFraction item)  method
## indexOf(MathFunction item)  method
## indexOf(MathGroupingCharacter item)  method
## indexOf(MathLeftSubSuperscriptElement item)  method
## indexOf(MathLimit item)  method
## indexOf(MathMatrix item)  method
## indexOf(MathNaryOperator item)  method
## indexOf(MathRadical item)  method
## indexOf(MathRightSubSuperscriptElement item)  method
## indexOf(MathSubscriptElement item)  method
## indexOf(MathSuperscriptElement item)  method

 Determines the index of a specific math element in collection.
 
Example:
 
```php
  $mathBlock = new MathBlock(new MathematicalText("x"));
  $plusElement = new MathematicalText("+");
  $mathBlock->add($plusElement);
  $mathBlock->add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
  $index = $mathBlock->indexOf($plusElement);
```

### Parameters

| Name | Description |
| --- | --- |
| item | The element to locate in the collection. |

### Returns
The index of item if found in the collection; otherwise, -1.


---


