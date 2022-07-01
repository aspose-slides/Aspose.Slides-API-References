---
title: insert
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 160
url: /php-java/mathblock/insert/
---

## insert(int index, BaseScript item)  method
## insert(int index, MathAccent item)  method
## insert(int index, MathArray item)  method
## insert(int index, MathBar item)  method
## insert(int index, MathBlock item)  method
## insert(int index, MathBorderBox item)  method
## insert(int index, MathBox item)  method
## insert(int index, MathDelimiter item)  method
## insert(int index, MathElementBase item)  method
## insert(int index, MathematicalText item)  method
## insert(int index, MathFraction item)  method
## insert(int index, MathFunction item)  method
## insert(int index, MathGroupingCharacter item)  method
## insert(int index, MathLeftSubSuperscriptElement item)  method
## insert(int index, MathLimit item)  method
## insert(int index, MathMatrix item)  method
## insert(int index, MathNaryOperator item)  method
## insert(int index, MathRadical item)  method
## insert(int index, MathRightSubSuperscriptElement item)  method
## insert(int index, MathSubscriptElement item)  method
## insert(int index, MathSuperscriptElement item)  method

 Inserts a MathElement into the collection at the specified index.
 
Example:
 
```php
  $mathBlock = new MathBlock(new MathematicalText("x"));
  $plusElement = new MathematicalText("+");
  $mathBlock->add($plusElement);
  $mathBlock->insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
```

### Parameters

| Name | Description |
| --- | --- |
| index | The zero-based index at which MathElement should be inserted. |
| item | The MathElement to insert. |


---


