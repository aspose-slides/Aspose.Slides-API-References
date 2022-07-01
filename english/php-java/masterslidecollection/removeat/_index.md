---
title: removeAt
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 100
url: /php-java/masterslidecollection/removeat/
---

## removeAt(int index)  method

 Removes the element at the specified index of the collection.
 

### Parameters

| Name | Description |
| --- | --- |
| index | The zero-based index of the element to remove. To avoid throwing of the PptxEditException check master's HasDependingSlides property before. |

### Exception

| Exception | Condition |
| --- | --- |
 | PptxEditException | Thrown if the master to remove is used in presentation (its HasDependingSlides property is true). |


---


