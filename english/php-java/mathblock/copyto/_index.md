---
title: copyTo
type: docs
weight: 70
url: /php-java/mathblock/copyto/
---

# copyTo(com.aspose.slides.IMathElement[], int) method

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

##  Parameters

| name | description |
| --- | --- |
| array | Array to copy to. |
| arrayIndex | Index to begin copying. |


