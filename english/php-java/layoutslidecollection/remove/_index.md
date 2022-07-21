---
title: remove
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 160
url: /php-java/layoutslidecollection/remove/
---

## remove([LayoutSlide](../../layoutslide) value)  method

 Removes a layout from the collection.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| value | [LayoutSlide](../../layoutslide) | The layout slide to remove from the collection. 1) To avoid throwing of the PptxEditException check layout's HasDependingSlides property before. 2) You can use also ILayoutSlide#remove method to simplify code. |

### Returns
void

### Exception

| Exception | Condition |
| --- | --- |
 | PptxEditException | Thrown if layout is used in presentation (its HasDependingSlides property is true). |


---


