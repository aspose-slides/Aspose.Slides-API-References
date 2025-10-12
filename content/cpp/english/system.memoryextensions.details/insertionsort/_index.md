---
title: InsertionSort()
second_title: Aspose.Slides for C++ API Reference
description: Performs insertion sort on key-value pairs.
type: docs
weight: 66
url: /system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) function


Performs insertion sort on key-value pairs.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
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