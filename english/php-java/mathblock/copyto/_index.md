---
title: copyTo
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 80
url: /php-java/mathblock/copyto/
---

## copyTo(com.aspose.slides.IMathElement[] array, int arrayIndex)  method

 Copy to specified array.
 
Example:
 
```php
  $mathBlock = new MathBlock(new MathematicalText("x"));
  $plusElement = new MathematicalText("+");
  $mathBlock->add($plusElement);
  $mathBlock->add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
  $destinationArray = new IMathElement[$mathBlock::$Count];
  $mathBlock->copyTo($destinationArray, 0);
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| array | com.aspose.slides.IMathElement[] | Array to copy to. |
| arrayIndex | int | Index to begin copying. |

### Returns
void


---


