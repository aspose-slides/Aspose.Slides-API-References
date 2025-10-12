---
title: PickPivotAndPartition()
second_title: Aspose.Slides for C++ API Reference
description: Selects pivot and partitions key-value pairs for quicksort.
type: docs
weight: 105
url: /system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) function


Selects pivot and partitions key-value pairs for quicksort.

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TKey | The type of keys |
| TValue | The type of values |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | The span of keys to partition |
| values | [Span](../../system/span/)\<TValue\>\& | The span of values to partition |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) function for keys |

### Return Value

The pivot index after partitioning

## See Also

* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)