---
title: getRect
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 110
url: /php-java/portion/getrect/
---

## getRect()  method

  Get coordinates of rect that bounds portion. The rect includes all the lines of
  text in portion, including empty ones.
  
Example:
 
```php
  $pres = new Presentation();
  try {
    $slide = $pres->getSlides()->get_Item(0);
    $shape = $slide->getShapes()->addAutoShape(ShapeType.Rectangle, 50, 50, 200, 50);
    $shape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->clear();
    $portion0 = new Portion("Some text");
    $portion1 = new Portion("GetRect text");
    $shape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->add($portion0);
    $shape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->add($portion1);
    $rect = $shape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->get_Item(1)->getRect();
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```


---


