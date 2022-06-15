---
title: removeAt
type: docs
weight: 150
url: /php-java/mathparagraph/removeat/
---

# removeAt(int) method

 Removes an item at the specified index of the collection.
 
Example:
 
```php
  $shape = $slide->getShapes()->addMathShape($x, $y, $width, $height);
  $mathParagraph = $shape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->get_Item(0)->getMathParagraph();
  $block = new MathBlock(new MathematicalText("y"));
  $mathParagraph->add($block);
  $mathParagraph->removeAt(0);
```

##  Parameters

| name | description |
| --- | --- |
| index | The zero-based index of the item to remove. |


