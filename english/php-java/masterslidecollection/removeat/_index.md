---
title: removeAt
type: docs
weight: 100
url: /php-java/masterslidecollection/removeat/
---

# removeAt(int) method

 Removes the element at the specified index of the collection.
 

##  Parameters

| name | description |
| --- | --- |
| index | The zero-based index of the element to remove. To avoid throwing of the PptxEditException check master's HasDependingSlides property before. |

##  Exception
PptxEditException Thrown if the master to remove is used in presentation (its HasDependingSlides property is true).


