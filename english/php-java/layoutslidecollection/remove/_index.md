---
title: remove
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 90
url: /php-java/layoutslidecollection/remove/
---

## remove([../../LayoutSlide]LayoutSlide value)  method

 Removes a layout from the collection.
 

### Parameters

| Name | Description |
| --- | --- |
| value | The layout slide to remove from the collection. 1) To avoid throwing of the PptxEditException check layout's HasDependingSlides property before. 2) You can use also ILayoutSlide#remove method to simplify code. |

### Exception

| Exception | Condition |
| --- | --- |
 | PptxEditException | Thrown if layout is used in presentation (its HasDependingSlides property is true). |


---


