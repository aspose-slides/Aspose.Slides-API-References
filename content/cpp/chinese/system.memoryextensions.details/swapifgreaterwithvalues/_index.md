---
title: SwapIfGreaterWithValues()
second_title: Aspose.Slides C++ API 参考
description: 在满足比较条件时交换键值对。
type: docs
weight: 53
url: /zh/system.memoryextensions.details/swapifgreaterwithvalues/
---
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) 函数

如果满足比较条件，则交换键值对。

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TKey | 键的类型 |
| TValue | 值的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 键的跨度 |
| values | [Span](../../system/span/)\<TValue\>\& | 值的跨度 |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) 键的函数 |
| i | **int32_t** | 要比较的第一个索引 |
| j | **int32_t** | 要比较的第二个索引 |

## 另请参阅

* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions::Details](../)
* 库 [Aspose.Slides](../../)