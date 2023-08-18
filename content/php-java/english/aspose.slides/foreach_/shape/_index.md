---
title: shape
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/foreach_/shape/
---

## shape([Presentation](../../presentation) pres, [ForEach_.ForEachShapeCallback](../../foreach_.foreachshapecallback) forEachShape)  method

 Iterate each  Shape in the  Presentation.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation to iterate layout shapes |
| forEachShape | [ForEach_.ForEachShapeCallback](../../foreach_.foreachshapecallback) | Callback that will be invoked for each shape Shapes will be iterated in all type of slides - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) and #layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### Returns
void


---


## shape([Presentation](../../presentation) pres, boolean includeNotes, [ForEach_.ForEachShapeCallback](../../foreach_.foreachshapecallback) forEachShape)  method

 Iterate each  Shape in the  Presentation.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation to iterate layout shapes |
| includeNotes | boolean | Flag that indicates whether NotesSlides should be included in processing. |
| forEachShape | [ForEach_.ForEachShapeCallback](../../foreach_.foreachshapecallback) | Callback that will be invoked for each shape Shapes will be iterated in all type of slides - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback), #layoutSlide(Presentation,ForEachLayoutSlideCallback) and NotesSlide if needed. |

### Returns
void


---


## shape([BaseSlide](../../baseslide) baseSlide, [ForEach_.ForEachShapeCallback](../../foreach_.foreachshapecallback) forEachShape)  method

 Iterate each  Shape in the  BaseSlide.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| baseSlide | [BaseSlide](../baseslide) | Slide to iterate layout shapes |
| forEachShape | [ForEach_.ForEachShapeCallback](../../foreach_.foreachshapecallback) | Callback that will be invoked for each shape BaseSlide is the base type for #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) and #layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### Returns
void


---


