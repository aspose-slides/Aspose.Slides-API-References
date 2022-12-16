---
title: setColumnCount
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 220
url: /php-java/textframeformat/setcolumncount/
---

## setColumnCount(int value)  method

 Returns or sets number of columns in the text area.
 This value must be a positive number. Otherwise, the value will be set to zero. 
 Value 0 means undefined value.
 Read/write  int.
 

 The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
 
```php
  $pres = new Presentation();
  try {
    $shape1 = $pres->getSlides()->get_Item(0)->getShapes()->addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
    $format = $shape1->getTextFrame()->getTextFrameFormat();
    $format->setColumnCount(2);
    $format->setColumnSpacing(20);
    $shape1->getTextFrame()->setText("All these columns are forced to stay within a single text container -- " + "you can add or delete text - and the new or remaining text automatically adjusts " + "itself to stay within the container. You cannot have text spill over from one container " + "to other, though -- because PowerPoint's column options for text are limited!");
    $pres->save("Columns_output.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
void


---


