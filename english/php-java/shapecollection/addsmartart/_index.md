---
title: addSmartArt
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 220
url: /php-java/shapecollection/addsmartart/
---

## addSmartArt(float, float, float, float, int) method

 Add SmartArt diagram.
 
Example:
 
```php
  $pres = new Presentation();
  $slide = $pres->getSlides()->get_Item(0);
  $smart = $slide->getShapes()->addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
```

### Parameters

| Name | Description |
| --- | --- |
| x | The X-coordinate for a left side of diagram's frame. |
| y | The Y-coordinate for a left side of diagram's frame. |
| width | The width of diagram's frame. |
| height | The height of diagram's frame. |
| layoutType | The type of SmartArt diagram |

### Returns
Create SmartArt diagram


---


