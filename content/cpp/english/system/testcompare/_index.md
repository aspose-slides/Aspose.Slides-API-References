---
title: TestCompare
second_title: Aspose.Slides for C++ API Reference
description: Service structure providing interface to compare collections.
type: docs
weight: 1769
url: /system/testcompare/
---
## TestCompare struct


Service structure providing interface to compare collections.

```cpp
class TestCompare
```

## Methods

| Method | Description |
| --- | --- |
| static **bool** [AbstractEqual](./abstractequal/)([SCG::ICollection](../../system.collections.generic/icollection/)\<T\> *const, [SCG::ICollection](../../system.collections.generic/icollection/)\<T\> *const) | Compares two collections of unknown type. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<U\>\>\&) | Compares arrays of non-pointers. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | Compares arrays of pointers. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<U\>\>\&) | Compares lists of non-pointers. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | Compares lists of pointers. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<T\>\>\&, const [System::ArrayPtr](../arrayptr/)\<U\>\&) | Compares lists with arrays in non-pointers elements case. |
| static **bool** [AreEqual](./areequal/)(const [System::ArrayPtr](../arrayptr/)\<T\>\&, const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<U\>\>\&) | Compares lists with arrays in non-pointers elements case. |
| static **bool** [AreEqual](./areequal/)(const [System::ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | Compares lists with arrays in pointers elements case. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [System::ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<U\>\>\&) | Compares lists with arrays in pointers elements case. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K, U\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K, U\>\>\&) | Compares dictionaries of non-pointer mapped types. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&) | Compares dictionaries of pointer mapped types. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K1, U1\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K2, U2\>\>\&) | Compares dictionaries of different types. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::HashSet](../../system.collections.generic/hashset/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::HashSet](../../system.collections.generic/hashset/)\<U\>\>\&) | Compares hashsets of non-pointers. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::HashSet](../../system.collections.generic/hashset/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::HashSet](../../system.collections.generic/hashset/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | Compares hashsets of pointers. |
| static **bool** [AreEqual](./areequal/)(const [SCG::QueuePtr](../../system.collections.generic/queueptr/)\<T\>\&, const [SCG::QueuePtr](../../system.collections.generic/queueptr/)\<U\>\&) | Compares queues of non-pointers. |
| static **bool** [AreEqual](./areequal/)(const [SCG::QueuePtr](../../system.collections.generic/queueptr/)\<[SharedPtr](../sharedptr/)\<T\>\>\&, const [SCG::QueuePtr](../../system.collections.generic/queueptr/)\<[SharedPtr](../sharedptr/)\<U\>\>\&) | Compares queues of pointers. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Stack](../../system.collections.generic/stack/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Stack](../../system.collections.generic/stack/)\<U\>\>\&) | Compares stacks of non-pointers. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Stack](../../system.collections.generic/stack/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Stack](../../system.collections.generic/stack/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | Compares stacks of pointers. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, U\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, U\>\>\&) | Compares sorted dictionaries of non-pointer mapped types. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&) | Compares sorted dictionaries of pointer mapped types. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\&) | Compares sorted dictionaries of different types. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K, U\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K, U\>\>\&) | Compares sorted lists of non-pointer mapped types. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&) | Compares sorted lists of pointer mapped types. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K1, U1\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K2, U2\>\>\&) | Compares sorted lists of different types. |
| static **bool** [AreEqual](./areequal/)(const [System::Collections::Specialized::StringCollectionPtr](../../system.collections.specialized/stringcollectionptr/)\&, const [System::Collections::Specialized::StringCollectionPtr](../../system.collections.specialized/stringcollectionptr/)\&) | Compares string collections. |
| static **bool** [AreEqual](./areequal/)(const [System::SharedPtr](../sharedptr/)\<[SCG::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&, const [System::SharedPtr](../sharedptr/)\<[SCG::IEnumerable](../../system.collections.generic/ienumerable/)\<U\>\>\&) | Compares IEnumerable instances. |
## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)