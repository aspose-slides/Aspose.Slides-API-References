---
title: addSectionZoomFrame
type: docs
weight: 200
url: /php-java/shapecollection/addsectionzoomframe/
---

# addSectionZoomFrame(float, float, float, float, com.aspose.slides.ISection) method

 Adds a new Section Zoom object to the end of a collection.
 

 This example demonstrates adding a Section Zoom object to the end of a collection
 (assume that there are at least two sections in the "Presentation.pptx" presentation):
 
```php
  $pres = new Presentation("Presentation.pptx");
  try {
    $zoomFrame = $pres->getSlides()->get_Item(0)->getShapes()->addSectionZoomFrame(150, 20, 50, 50, $pres->getSections()->get_Item(1));
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

##  Parameters

| name | description |
| --- | --- |
| x | X coordinate of a new Section Zoom frame float. |
| y | Y coordinate of a new Section Zoom frame float. |
| width | Width of a new Section Zoom frame float. |
| height | Height of a new Section Zoom frame float. |
| section | The section object referenced by the Section Zoom frame ISection. |

##  Returns
Created Section Zoom object ISectionZoomFrame.

##  Exception
ArgumentException Referenced section does not belong to the current presentation or does not contains any slides.


# addSectionZoomFrame(float, float, float, float, com.aspose.slides.ISection, com.aspose.slides.IPPImage) method

 Adds a new Section Zoom object to the end of a collection with a predefined image.
 

 This example demonstrates adding a Section Zoom object to the end of a collection
 (assume that there are at least two sections in the "Presentation.pptx" presentation):
 
```php
  $pres = new Presentation("Presentation.pptx");
  try {
    $image = $pres->getImages()->addImage(Files->readAllBytes(Paths->get("image.png")));
    $zoomFrame = $pres->getSlides()->get_Item(0)->getShapes()->addSectionZoomFrame(150, 20, 50, 50, $pres->getSections()->get_Item(1), $image);
  } catch (JavaException $e) {
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

##  Parameters

| name | description |
| --- | --- |
| x | X coordinate of a new Section Zoom frame float. |
| y | Y coordinate of a new Section Zoom frame float. |
| width | Width of a new Section Zoom frame float. |
| height | Height of a new Section Zoom frame float. |
| section | The section object referenced by the Section Zoom frame ISection. |
| image | The image for the referenced slide IPPImage |

##  Returns
Created Section Zoom object ISectionZoomFrame.

##  Exception
ArgumentException Referenced section does not belong to the current presentation or does not contains any slides.

