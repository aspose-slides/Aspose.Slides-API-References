---
title: SequenceEqualImpl()
second_title: Aspose.Slides for C++ API Reference
description: Checks if two spans are equal starting from specified positions.
type: docs
weight: 27
url: /system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) function


Checks if two spans are equal starting from specified positions.

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type of elements in spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | First span |
| start | const **int32_t** | Starting index in first span |
| length | **int32_t** | Number of elements to compare |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Second span |

### Return Value

true if the specified ranges are equal, false otherwise

## See Also

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)