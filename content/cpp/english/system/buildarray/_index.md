---
title: BuildArray()
second_title: Aspose.Slides for C++ API Reference
description: Build an array.
type: docs
weight: 2224
url: /system/buildarray/
---
## System::BuildArray() function


Build an array.

```cpp
template<typename T> Details::ObjectBuilder<Details::ArrayStorage<T>> System::BuildArray()
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Element type of array to build |

### Return Value

ObjectBuilder configured for array construction
## Remarks



Creates a ArrayPtr<T> and returns a builder for it 
[Object](../object/) construction must be finished with [Get()](../get/) call 

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)