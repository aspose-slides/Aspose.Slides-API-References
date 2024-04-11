---
title: copy_to method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.animation/behaviorcollection/copy_to/
weight: 50
---


## copy_to {#listibehavior-int}
Copies the elements of the .NET type System.Collections.Generic.ICollection`1 to an .NET type System.Array, starting at a particular .NET type System.Array index.


```python
def copy_to(self, array, array_index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| array | List[IBehavior] | The one-dimensional .NET type System.Array that is the destination of the elements copied from .NET type System.Collections.Generic.ICollection`1. The .NET type System.Array must have zero-based indexing. |
| array_index | int | The zero-based index in `<br/><br/>array`<br/><br/> at which copying begins. |

## Exceptions

| Exception | Description |
| :- | :- |
| .NET type System.ArgumentNullException | `<br/>array`<br/> is null. |
| .NET type System.ArgumentOutOfRangeException | `<br/>array_index`<br/> is less than 0. |
| .NET type System.ArgumentException | The number of elements in the source .NET type System.Collections.Generic.ICollection`1 is greater than the available space from `<br/>array_index`<br/> to the end of the destination `<br/>array`<br/>. |



