---
title: removeAt
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 50
url: /php-java/masterlayoutslidecollection/removeat/
---

## removeAt(int) method

 Removes the element at the specified index of the collection.
 

### Parameters

| Name | Description |
| --- | --- |
| index | The zero-based index of the element to remove. 1) To avoid throwing of the PptxEditException check layout's HasDependingSlides property before. 2) You can use also ILayoutSlide#remove method to simplify code. |

### Exception

| Exception | Condition |
| --- | --- |
 | PptxEditException | Thrown if layout is used in presentation (its HasDependingSlides property is true). |


---


