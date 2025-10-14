---
title: Heapify()
second_title: Aspose.Slides for C++ API Reference
description: Maintains heap property for key-value pairs.
type: docs
weight: 92
url: /system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) function


Maintains heap property for key-value pairs.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TKey | The type of keys |
| TValue | The type of values |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | The span of keys in the heap |
| values | [Span](../../system/span/)\<TValue\>\& | The span of values in the heap |
| n | **int32_t** | Size of the heap |
| i | **int32_t** | Index to heapify from |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) function for keys |

## See Also

* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)