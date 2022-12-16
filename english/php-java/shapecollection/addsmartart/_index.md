---
title: addSmartArt
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 220
url: /php-java/shapecollection/addsmartart/
---

## addSmartArt(float x, float y, float width, float height, int layoutType)  method

 Add SmartArt diagram.
 
Example:
 
```php
  $pres = new Presentation();
  try {
    $slide = $pres->getSlides()->get_Item(0);
    $smart = $slide->getShapes()->addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | float | The X-coordinate for a left side of diagram's frame. |
| y | float | The Y-coordinate for a left side of diagram's frame. |
| width | float | The width of diagram's frame. |
| height | float | The height of diagram's frame. |
| layoutType | int | The type of SmartArt diagram |

### Returns
[SmartArt](../../smartart)


---


