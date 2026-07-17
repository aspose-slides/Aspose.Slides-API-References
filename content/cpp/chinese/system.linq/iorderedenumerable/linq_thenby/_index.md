---
title: LINQ_ThenBy()
second_title: Aspose.Slides C++ API 参考
description: 根据键对序列中的元素执行后续升序排序。
type: docs
weight: 27
url: /zh/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) method

对序列中的元素执行后续排序，按照键以升序排列。

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Key | keySelector 返回的键的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | 用于从每个元素中提取键的函数。 |

### 返回值

[System::Linq::IOrderedEnumerable](../) 其元素按照键排序。

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) method

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## 另请参见

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [IOrderedEnumerable](../)
* 类 [Func](../../../system/func/)
* 命名空间 [System::Linq](../../)
* 库 [Aspose.Slides](../../../)