---
title: BuildObject()
second_title: Aspose.Slides for C++ API Reference
description: Build an object with shared ownership.
type: docs
weight: 2198
url: /system/buildobject/
---
## System::BuildObject(Args\&&...) function


Build an object with shared ownership.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type of object to build |
| Args | Argument types for object construction |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| args | Args\&&... | Arguments to forward to object constructor |

### Return Value

ObjectBuilder configured for shared pointer construction
## Remarks



Creates a SharedPtr<T> and returns a builder for it 
[Object](../object/) construction must be finished with [Get()](../get/) call 

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)