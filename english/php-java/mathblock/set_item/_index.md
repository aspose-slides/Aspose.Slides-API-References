---
title: set_Item
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 250
url: /php-java/mathblock/set_item/
---

## set_Item(int index, BaseScript value)  method
## set_Item(int index, MathAccent value)  method
## set_Item(int index, MathArray value)  method
## set_Item(int index, MathBar value)  method
## set_Item(int index, MathBlock value)  method
## set_Item(int index, MathBorderBox value)  method
## set_Item(int index, MathBox value)  method
## set_Item(int index, MathDelimiter value)  method
## set_Item(int index, MathElementBase value)  method
## set_Item(int index, MathematicalText value)  method
## set_Item(int index, MathFraction value)  method
## set_Item(int index, MathFunction value)  method
## set_Item(int index, MathGroupingCharacter value)  method
## set_Item(int index, MathLeftSubSuperscriptElement value)  method
## set_Item(int index, MathLimit value)  method
## set_Item(int index, MathMatrix value)  method
## set_Item(int index, MathNaryOperator value)  method
## set_Item(int index, MathRadical value)  method
## set_Item(int index, MathRightSubSuperscriptElement value)  method
## set_Item(int index, MathSubscriptElement value)  method
## set_Item(int index, MathSuperscriptElement value)  method

 Gets or sets IMathElement at the specified index.
 
Example:
 
```php
  $mathBlock = new MathBlock(new MathematicalText("x"));
  $firstElem = $mathBlock->get_Item(0);
```

### Parameters

| Name | Description |
| --- | --- |
| value | The mathematical element. |
| index | The zero-based index of the item |


---


