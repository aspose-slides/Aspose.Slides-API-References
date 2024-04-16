---
title: copy_to method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.animation/behaviorcollection/copy_to/
weight: 40
---


## copy_to {#listibehavior-int}
Copies the elements of the **System.Collections.Generic.ICollection`1** to an **System.Array**, starting at a particular **System.Array** index.


```python
def copy_to(self, array, array_index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| array | **List[IBehavior]** | The one-dimensional **System.Array** that is the destination of the elements copied from **System.Collections.Generic.ICollection`1**. The **System.Array** must have zero-based indexing. |
| array_index | **int** | The zero-based index in `<br/><br/>array`<br/><br/> at which copying begins. |

## Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `<br/>array`<br/> is null. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `<br/>array_index`<br/> is less than 0. |
| **RuntimeError(Proxy error(ArgumentException))** | The number of elements in the source **System.Collections.Generic.ICollection`1** is greater than the available space from `<br/>array_index`<br/> to the end of the destination `<br/>array`<br/>. |



### See Also
* class [`BehaviorCollection`](/slides/python-net/aspose.slides.animation/behaviorcollection)
* module [`aspose.slides.animation`](/slides/python-net/aspose.slides.animation)
* library [`Aspose.Slides`](/slides/python-net)

