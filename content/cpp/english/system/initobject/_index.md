---
title: InitObject()
second_title: Aspose.Slides for C++ API Reference
description: Starts initialization of an object with shared ownership.
type: docs
weight: 2211
url: /system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) function


Starts initialization of an object with shared ownership.

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type of object to initialize |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) to initialize |

### Return Value

ObjectBuilder configured for shared pointer construction
## Remarks



[Object](../object/) initialization must be finished with [Get()](../get/) call 

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)