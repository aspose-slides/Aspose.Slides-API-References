---
title: BinarySearchImpl()
second_title: Aspose.Slides for C++ API Reference
description: Common binary search implementation.
type: docs
weight: 118
url: /system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) function


Common binary search implementation.

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type of elements in span |
| TValue | Type of value to search for |
| TCompareFunc | Function type for comparison |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search |
| value | const TValue\& | The value to search for |
| compareFunc | TCompareFunc | Function that compares value with span element and returns **int32_t** (-1, 0, 1) |

### Return Value

Index of found element or bitwise complement of insertion point

## See Also

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)