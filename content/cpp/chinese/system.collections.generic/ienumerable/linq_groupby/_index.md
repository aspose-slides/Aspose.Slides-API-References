---
title: LINQ_GroupBy()
second_title: Aspose.Slides C++ API 参考
description: 对序列中的元素进行分组。
type: docs
weight: 287
url: /zh/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) 方法

对序列中的元素进行分组。

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Key | keyPredicate 返回的键的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | 用于提取每个元素的键的函数。 |

### 返回值

一个包含对象序列和键的 [IEnumerable](../)

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) 方法

对序列中的元素进行分组。

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Key | keyPredicate 返回的键的类型 |
| Element | elementSelector 返回的元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | 用于提取每个元素的键的函数。 |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | 用于提取每个元素的值键的函数。 |

### 返回值

一个包含对象序列和键的 [IEnumerable](../)

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) 方法




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) 方法




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IEnumerable](../)
* 类 [IGrouping](../../../system.linq/igrouping/)
* 类 [Func](../../../system/func/)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)