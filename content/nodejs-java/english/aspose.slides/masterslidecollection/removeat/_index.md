---
title: removeAt
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/masterslidecollection/removeat/
---

## removeAt(int index)  function

 Removes the element at the specified index of the collection.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. To avoid throwing of the PptxEditException check master's HasDependingSlides property before. |

### Error

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if the master to remove is used in presentation (its HasDependingSlides property is true). |


---


