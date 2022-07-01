---
title: contains
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 60
url: /php-java/mathblock/contains/
---

## contains(BaseScript item)  method
## contains(MathAccent item)  method
## contains(MathArray item)  method
## contains(MathBar item)  method
## contains(MathBlock item)  method
## contains(MathBorderBox item)  method
## contains(MathBox item)  method
## contains(MathDelimiter item)  method
## contains(MathElementBase item)  method
## contains(MathematicalText item)  method
## contains(MathFraction item)  method
## contains(MathFunction item)  method
## contains(MathGroupingCharacter item)  method
## contains(MathLeftSubSuperscriptElement item)  method
## contains(MathLimit item)  method
## contains(MathMatrix item)  method
## contains(MathNaryOperator item)  method
## contains(MathRadical item)  method
## contains(MathRightSubSuperscriptElement item)  method
## contains(MathSubscriptElement item)  method
## contains(MathSuperscriptElement item)  method

 Determines whether the collection contains a specific value.
 
Example:
 
```php
  $mathBlock = new MathBlock(new MathematicalText("x"));
  $plusElement = new MathematicalText("+");
  $mathBlock->Add($plusElement);
  $mathBlock->Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
  $contains = $mathBlock->Contains($plusElement);
```

### Parameters

| Name | Description |
| --- | --- |
| item | The object to locate in the collection. |

### Returns
true if item is found in the collection; otherwise, false.


---


