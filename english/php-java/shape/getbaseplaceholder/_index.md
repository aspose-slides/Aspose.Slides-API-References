---
title: getBasePlaceholder
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 40
url: /php-java/shape/getbaseplaceholder/
---

## getBasePlaceholder()  method

 Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).
  
 A null is returned if the current shape is not inherited.

 
```php
  // get all (master/layout/slide) animated effects of the placeholder shape
  $pres = new Presentation("sample.pptx");
  try {
    $slide = $pres->getSlides()->get_Item(0);
    $shape = $slide->getShapes()->get_Item(0);
    $shapeEffects = $slide->getLayoutSlide()->getTimeline()->getMainSequence()->getEffectsByShape($shape);
    $layoutShape = $shape->getBasePlaceholder();
    $layoutShapeEffects = $slide->getLayoutSlide()->getTimeline()->getMainSequence()->getEffectsByShape($layoutShape);
    $masterShape = $layoutShape->getBasePlaceholder();
    $masterShapeEffects = $slide->getLayoutSlide()->getMasterSlide()->getTimeline()->getMainSequence()->getEffectsByShape($masterShape);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
[GraphicalObject](../../graphicalobject), [Connector](../../connector), [Table](../../table), [SmartArtShape](../../smartartshape), [Shape](../../shape), [Ink](../../ink), [SummaryZoomFrame](../../summaryzoomframe), [GeometryShape](../../geometryshape), [ZoomFrame](../../zoomframe), [SummaryZoomSection](../../summaryzoomsection), [VideoFrame](../../videoframe), [OleObjectFrame](../../oleobjectframe), [SmartArt](../../smartart), [GroupShape](../../groupshape), [AutoShape](../../autoshape), [PictureFrame](../../pictureframe), [SectionZoomFrame](../../sectionzoomframe), [Chart](../../chart), [AudioFrame](../../audioframe), [LegacyDiagram](../../legacydiagram), [ZoomObject](../../zoomobject)


---


