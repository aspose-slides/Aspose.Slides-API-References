---
title: shape
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 60
url: /php-java/foreach/shape/
---


 Iterate each  Shape in the  Presentation.
 

 
```php
  $pres = new Presentation("pres.pptx");
```

### Parameters

| Name | Description |
| --- | --- |
| pres | Presentation to iterate layout shapes |
| forEachShape | Callback that will be invoked for each shape Shapes will be iterated in all type of slides - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) and #layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### Returns
Presentation


---



 Iterate each  Shape in the  BaseSlide.
 

 
```php
  $pres = new Presentation("pres.pptx");
```

### Parameters

| Name | Description |
| --- | --- |
| baseSlide | Slide to iterate layout shapes |
| forEachShape | Callback that will be invoked for each shape BaseSlide is the base type for #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) and #layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### Returns
BaseSlide


---


