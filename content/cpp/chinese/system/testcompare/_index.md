---
title: TestCompare
second_title: Aspose.Slides for C++ API 参考
description: 提供用于比较集合的接口的服务结构体。
type: docs
weight: 1886
url: /zh/system/testcompare/
---
## TestCompare 结构体

提供用于比较集合的接口的服务结构体。

```cpp
class TestCompare
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static **bool** [AbstractEqual](./abstractequal/)([SCG::ICollection](../../system.collections.generic/icollection/)\<T\> *const, [SCG::ICollection](../../system.collections.generic/icollection/)\<T\> *const) | 比较未知类型的两个集合。 |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<U\>\>\&) | 比较非指针数组。 |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | 比较指针数组。 |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<U\>\>\&) | 比较非指针列表。 |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | 比较指针列表。 |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<T\>\>\&, const [System::ArrayPtr](../arrayptr/)\<U\>\&) | 比较非指针元素情况下的列表与数组。 |
| static **bool** [AreEqual](./areequal/)(const [System::ArrayPtr](../arrayptr/)\<T\>\&, const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<U\>\>\&) | 比较非指针元素情况下的列表与数组。 |
| static **bool** [AreEqual](./areequal/)(const [System::ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | 比较指针元素情况下的列表与数组。 |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [System::ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<U\>\>\&) | 比较指针元素情况下的列表与数组。 |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K, U\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K, U\>\>\&) | 比较非指针映射类型的字典。 |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&) | 比较指针映射类型的字典。 |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K1, U1\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K2, U2\>\>\&) | 比较不同类型的字典。 |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::HashSet](../../system.collections.generic/hashset/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::HashSet](../../system.collections.generic/hashset/)\<U\>\>\&) | 比较非指针哈希集。 |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::HashSet](../../system.collections.generic/hashset/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::HashSet](../../system.collections.generic/hashset/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | 比较指针哈希集。 |
| static **bool** [AreEqual](./areequal/)(const [SCG::QueuePtr](../../system.collections.generic/queueptr/)\<T\>\&, const [SCG::QueuePtr](../../system.collections.generic/queueptr/)\<U\>\&) | 比较非指针队列。 |
| static **bool** [AreEqual](./areequal/)(const [SCG::QueuePtr](../../system.collections.generic/queueptr/)\<[SharedPtr](../sharedptr/)\<T\>\>\&, const [SCG::QueuePtr](../../system.collections.generic/queueptr/)\<[SharedPtr](../sharedptr/)\<U\>\>\&) | 比较指针队列。 |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Stack](../../system.collections.generic/stack/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Stack](../../system.collections.generic/stack/)\<U\>\>\&) | 比较非指针栈。 |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Stack](../../system.collections.generic/stack/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Stack](../../system.collections.generic/stack/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | 比较指针栈。 |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, U\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, U\>\>\&) | 比较非指针映射类型的已排序字典。 |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&) | 比较指针映射类型的已排序字典。 |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\&) | 比较不同类型的已排序字典。 |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K, U\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K, U\>\>\&) | 比较非指针映射类型的已排序列表。 |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&) | 比较指针映射类型的已排序列表。 |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K1, U1\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K2, U2\>\>\&) | 比较不同类型的已排序列表。 |
| static **bool** [AreEqual](./areequal/)(const [System::Collections::Specialized::StringCollectionPtr](../../system.collections.specialized/stringcollectionptr/)\&, const [System::Collections::Specialized::StringCollectionPtr](../../system.collections.specialized/stringcollectionptr/)\&) | 比较字符串集合。 |
| static **bool** [AreEqual](./areequal/)(const [System::SharedPtr](../sharedptr/)\<[SCG::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&, const [System::SharedPtr](../sharedptr/)\<[SCG::IEnumerable](../../system.collections.generic/ienumerable/)\<U\>\>\&) | 比较 IEnumerable 实例。 |
## 另请参阅

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)