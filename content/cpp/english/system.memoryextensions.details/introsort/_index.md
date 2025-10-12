---
title: IntroSort()
second_title: Aspose.Slides for C++ API Reference
description: Internal implementation of introsort algorithm for key-value pairs.
type: docs
weight: 40
url: /system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) function


Internal implementation of introsort algorithm for key-value pairs.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
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
| depthLimit | **int32_t** | Maximum recursion depth before switching to heapsort |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) function for keys |

## See Also

* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)