---
title: PickPivotAndPartition()
second_title: Aspose.Slides for C++ API 参考
description: 为快速排序选择枢轴并划分键值对。
type: docs
weight: 105
url: /zh/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)> ) 函数

选择枢轴并对键值对进行快速排序的划分。

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TKey | 键的类型 |
| TValue | 值的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 要划分的键的 span |
| values | [Span](../../system/span/)\<TValue\>\& | 要划分的值的 span |
| comparer | std::function\<int32_t(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) 用于键的函数 |

### 返回值

划分后枢轴的索引

## 另请参阅

* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions::Details](../)
* 库 [Aspose.Slides](../../)