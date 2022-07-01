---
title: add
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 40
url: /php-java/mathblock/add/
---

## add(BaseScript item)  method
## add(MathAccent item)  method
## add(MathArray item)  method
## add(MathBar item)  method
## add(MathBlock item)  method
## add(MathBorderBox item)  method
## add(MathBox item)  method
## add(MathDelimiter item)  method
## add(MathElementBase item)  method
## add(MathematicalText item)  method
## add(MathFraction item)  method
## add(MathFunction item)  method
## add(MathGroupingCharacter item)  method
## add(MathLeftSubSuperscriptElement item)  method
## add(MathLimit item)  method
## add(MathMatrix item)  method
## add(MathNaryOperator item)  method
## add(MathRadical item)  method
## add(MathRightSubSuperscriptElement item)  method
## add(MathSubscriptElement item)  method
## add(MathSuperscriptElement item)  method

 Adds a math element to the end of the collection.
 
Example:
 
```php
  $mathBlock = new MathBlock(new MathematicalText("x"));
  $mathBlock->add(new MathematicalText("+"));
  $mathBlock->add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
```

### Parameters

| Name | Description |
| --- | --- |
| item | The IMathElement to be added to the end of the collection. |


---


