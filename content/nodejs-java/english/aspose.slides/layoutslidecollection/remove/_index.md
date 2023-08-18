---
title: remove
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/layoutslidecollection/remove/
---

## remove([LayoutSlide](../../layoutslide) value)  function

 Removes a layout from the collection.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| value | [LayoutSlide](../../layoutslide) | The layout slide to remove from the collection. 1) To avoid throwing of the PptxEditException check layout's HasDependingSlides property before. 2) You can use also ILayoutSlide#remove function to simplify code. |

### Error

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if layout is used in presentation (its HasDependingSlides property is true). |


---


