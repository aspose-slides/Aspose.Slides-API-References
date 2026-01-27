---
title: Build()
second_title: Aspose.Slides for C++ API Reference
description: Build an object with direct ownership.
type: docs
weight: 2237
url: /system/build/
---
## System::Build(Args\&&...) function


Build an object with direct ownership.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
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

ObjectBuilder configured for direct object construction
## Remarks



[Object](../object/) construction must be finished with [Get()](../get/) call 

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)