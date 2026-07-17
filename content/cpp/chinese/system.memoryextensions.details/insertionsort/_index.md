---
title: InsertionSort()
second_title: Aspose.Slides for C++ API 参考
description: 对键-值对执行插入排序。
type: docs
weight: 66
url: /zh/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) 函数

对键-值对执行插入排序。

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
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
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) 函数用于键 |

## 参见

* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions::Details](../)
* 库 [Aspose.Slides](../../)