---
title: IntroSort()
second_title: Aspose.Slides for C++ API 参考
description: 键值对的 introsort 算法内部实现。
type: docs
weight: 40
url: /zh/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) function

键值对的 introsort 算法的内部实现。

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TKey | 键的类型 |
| TValue | 值的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 要排序的键的跨度 |
| values | [Span](../../system/span/)\<TValue\>\& | 要排序的值的跨度 |
| depthLimit | **int32_t** | 切换到 heapsort 前的最大递归深度 |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) 键的函数 |

## 另请参阅

* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions::Details](../)
* 库 [Aspose.Slides](../../)