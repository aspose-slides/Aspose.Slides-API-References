---
title: LastIndexOfImpl()
second_title: Aspose.Slides for C++ API Reference
description: Finds the last index of a value in a span.
type: docs
weight: 14
url: /system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) function


Finds the last index of a value in a span.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type of elements in span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) to search |
| length | **int32_t** | Length to search within |
| value | const T\& | Value to find |

### Return Value

Last index of the value, or -1 if not found

## See Also

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)