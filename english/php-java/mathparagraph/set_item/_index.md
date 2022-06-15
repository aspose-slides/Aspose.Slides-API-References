---
title: set_Item
type: docs
weight: 170
url: /php-java/mathparagraph/set_item/
---

# set_Item(int, com.aspose.slides.IMathBlock) method

 Gets the item at the specified index.
 Read-only  IMathBlock.
 
Example:
 
```php
  $shape = $slide->getShapes()->addMathShape($x, $y, $width, $height);
  $mathParagraph = $shape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->get_Item(0)->getMathParagraph();
  $mathParagraph->add(new MathBlock(new MathematicalText("block1")));
  $mathParagraph->add(new MathBlock(new MathematicalText("block2")));
  $block = $mathParagraph->get_Item(1);
```

##  Parameters

| name | description |
| --- | --- |
| value | The block of a mathematical text. |
| index | The zero-based index of the item to get |

##  Returns
IMathBlock


