---
title: HeapSort()
second_title: Aspose.Slides for C++ API Reference
description: Performs heap sort on key-value pairs.
type: docs
weight: 79
url: /system.memoryextensions.details/heapsort/
---
## System::MemoryExtensions::Details::HeapSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) function


Performs heap sort on key-value pairs.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::HeapSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TKey | The type of keys |
| TValue | The type of values |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | The span of keys to sort |
| values | [Span](../../system/span/)\<TValue\>\& | The span of values to sort |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) function for keys |

## See Also

* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)