---
title: removeAt
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/masterlayoutslidecollection/removeat/
---

## removeAt(int index)  method

 Removes the element at the specified index of the collection.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. 1) To avoid throwing of the PptxEditException check layout's HasDependingSlides property before. 2) You can use also ILayoutSlide#remove method to simplify code. |

### Returns
void

### Exception

| Exception | Condition |
| --- | --- |
 | PptxEditException | Thrown if layout is used in presentation (its HasDependingSlides property is true). |


---


