---
title: LINQ_OrderByDescending()
second_title: Aspose.Slides for C++ API 参考
description: 根据 keySelector 选取的键值，以降序对序列的元素进行排序。
type: docs
weight: 222
url: /zh/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) 方法


按 keySelector 选取的键值，以降序对序列的元素进行排序。

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| keySelector | 用于从元素中提取键的函数。 |

### 返回值

返回一个 IOrderedEnumerable，其元素已按键的降序排序。

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) 方法




```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## 另请参阅

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* 类 [Func](../../../system/func/)
* 类 [IEnumerable](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)