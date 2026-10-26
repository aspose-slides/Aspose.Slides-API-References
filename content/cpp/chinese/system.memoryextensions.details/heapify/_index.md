---
title: Heapify()
second_title: Aspose.Slides for C++ API 参考
description: 维护键值对的堆属性。
type: docs
weight: 92
url: /zh/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) 函数

维护键值对的堆属性。

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TKey | 键的类型 |
| TValue | 值的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 堆中键的跨度 |
| values | [Span](../../system/span/)\<TValue\>\& | 堆中值的跨度 |
| n | **int32_t** | 堆的大小 |
| i | **int32_t** | 要进行堆化的索引 |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) 用于键的函数 |

## 另请参阅

* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions::Details](../)
* 库 [Aspose.Slides](../../)