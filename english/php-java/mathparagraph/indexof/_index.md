---
title: indexOf
type: docs
weight: 100
url: /php-java/mathparagraph/indexof/
---

# indexOf(com.aspose.slides.IMathBlock) method

 Determines the index of a specific IMathBlock in collection.
 
Example:
 
```php
  $shape = $slide->getShapes()->addMathShape($x, $y, $width, $height);
  $mathParagraph = $shape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->get_Item(0)->getMathParagraph();
  $block = new MathBlock(new MathematicalText("y"));
  $mathParagraph->add($block);
  $index = $mathParagraph->indexOf($block);
```

##  Parameters

| name | description |
| --- | --- |
| mathBlock | The item to locate in the collection. |

##  Returns
The index of mathBlock if found in the collection; otherwise, -1.

