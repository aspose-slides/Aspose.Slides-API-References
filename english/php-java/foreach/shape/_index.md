---
title: shape
type: docs
weight: 60
url: /php-java/foreach/shape/
---

# shape(com.aspose.slides.Presentation, com.aspose.slides.ForEach.ForEachShapeCallback) method

 Iterate each  Shape in the  Presentation.
 

 
```php
  $pres = new Presentation("pres.pptx");
```

##  Parameters

| name | description |
| --- | --- |
| pres | Presentation to iterate layout shapes |
| forEachShape | Callback that will be invoked for each shape Shapes will be iterated in all type of slides - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) and #layoutSlide(Presentation,ForEachLayoutSlideCallback) |

##  Returns
Presentation


# shape(com.aspose.slides.BaseSlide, com.aspose.slides.ForEach.ForEachShapeCallback) method

 Iterate each  Shape in the  BaseSlide.
 

 
```php
  $pres = new Presentation("pres.pptx");
```

##  Parameters

| name | description |
| --- | --- |
| baseSlide | Slide to iterate layout shapes |
| forEachShape | Callback that will be invoked for each shape BaseSlide is the base type for #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) and #layoutSlide(Presentation,ForEachLayoutSlideCallback) |

##  Returns
BaseSlide


