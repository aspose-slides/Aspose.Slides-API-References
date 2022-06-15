---
title: joinBlock
type: docs
weight: 220
url: /php-java/mathblock/joinblock/
---

# joinBlock(com.aspose.slides.IMathBlock) method

 Joins another mathematical block with this one 
 
Example:
 
```php
  $block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2"))->join(new MathematicalText("="));
  $block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2"))->join(new MathematicalText("+"))->join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
  $block3 = $block1->joinBlock($block2);
```

##  Parameters

| name | description |
| --- | --- |
| other | The joining block |

##  Returns
this mathematical block after joining


