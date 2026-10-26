---
title: LINQ_OrderBy()
second_title: Aspose.Slides for C++ API 参考
description: 根据 keySelector 选择的键值，对序列中的元素进行升序排序。
type: docs
weight: 209
url: /zh/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) 方法

对序列中的元素进行升序排序，排序依据由 keySelector 选择的键值。

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| keySelector | 提取元素键的函数。 |

### 返回值

一个 IOrderedEnumerable，其元素已根据键进行排序

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) 方法

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* 类 [Func](../../../system/func/)
* 类 [IEnumerable](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)