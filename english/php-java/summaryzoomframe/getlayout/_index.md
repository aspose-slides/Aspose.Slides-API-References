---
title: getLayout
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 20
url: /php-java/summaryzoomframe/getlayout/
---

## getLayout()  method

 Gets layout of Summary Zoom Sections in the frame.
 Default value is GridLayout.
 
The example demonstrates getting Summary Zoom Section element by index:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $zoomFrame = $pres->getSlides()->get_Item(1)->getShapes()->get_Item(0);
    $layout = $zoomFrame->getLayout();
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
int


---


