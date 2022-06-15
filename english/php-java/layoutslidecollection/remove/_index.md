---
title: remove
type: docs
weight: 90
url: /php-java/layoutslidecollection/remove/
---

# remove(com.aspose.slides.ILayoutSlide) method

 Removes a layout from the collection.
 

##  Parameters

| name | description |
| --- | --- |
| value | The layout slide to remove from the collection. 1) To avoid throwing of the PptxEditException check layout's HasDependingSlides property before. 2) You can use also ILayoutSlide#remove method to simplify code. |

##  Exception
PptxEditException Thrown if layout is used in presentation (its HasDependingSlides property is true).


