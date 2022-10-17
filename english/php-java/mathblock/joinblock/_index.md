---
title: joinBlock
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 220
url: /php-java/mathblock/joinblock/
---

## joinBlock([MathBlock](../../mathblock) other)  method

 Joins another mathematical block with this one 
 
Example:
 
```php
  $block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2"))->join(new MathematicalText("="));
  $block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2"))->join(new MathematicalText("+"))->join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
  $block3 = $block1->joinBlock($block2);
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| other | [MathBlock](../../mathblock) | The joining block |

### Returns
[MathBlock](../../mathblock)


---


