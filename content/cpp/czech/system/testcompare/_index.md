---
title: TestCompare
second_title: Aspose.Slides pro C++ API Reference
description: Služební struktura poskytující rozhraní pro porovnání kolekcí.
type: docs
weight: 1912
url: /cs/system/testcompare/
---
## TestCompare struktura

Služební struktura poskytující rozhraní pro porovnání kolekcí.

```cpp
class TestCompare
```

## Metody

| Metoda | Popis |
| --- | --- |
| static **bool** [AbstractEqual](./abstractequal/)([SCG::ICollection](../../system.collections.generic/icollection/)\<T\> *const, [SCG::ICollection](../../system.collections.generic/icollection/)\<T\> *const) | Porovnává dvě kolekce neznámého typu. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<U\>\>\&) | Porovnává pole neukazatelů. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | Porovnává pole ukazatelů. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<U\>\>\&) | Porovnává seznamy neukazatelů. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | Porovnává seznamy ukazatelů. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<T\>\>\&, const [System::ArrayPtr](../arrayptr/)\<U\>\&) | Porovnává seznamy s poli v případě neukazatelových prvků. |
| static **bool** [AreEqual](./areequal/)(const [System::ArrayPtr](../arrayptr/)\<T\>\&, const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<U\>\>\&) | Porovnává seznamy s poli v případě neukazatelových prvků. |
| static **bool** [AreEqual](./areequal/)(const [System::ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | Porovnává seznamy s poli v případě ukazatelových prvků. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [System::ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<U\>\>\&) | Porovnává seznamy s poli v případě ukazatelových prvků. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K, U\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K, U\>\>\&) | Porovnává slovníky neukazatelových mapovacích typů. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&) | Porovnává slovníky ukazatelových mapovacích typů. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K1, U1\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K2, U2\>\>\&) | Porovnává slovníky různých typů. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::HashSet](../../system.collections.generic/hashset/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::HashSet](../../system.collections.generic/hashset/)\<U\>\>\&) | Porovnává hashsety neukazatelů. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::HashSet](../../system.collections.generic/hashset/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::HashSet](../../system.collections.generic/hashset/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | Porovnává hashsety ukazatelů. |
| static **bool** [AreEqual](./areequal/)(const [SCG::QueuePtr](../../system.collections.generic/queueptr/)\<T\>\&, const [SCG::QueuePtr](../../system.collections.generic/queueptr/)\<U\>\&) | Porovnává fronty neukazatelů. |
| static **bool** [AreEqual](./areequal/)(const [SCG::QueuePtr](../../system.collections.generic/queueptr/)\<[SharedPtr](../sharedptr/)\<T\>\>\&, const [SCG::QueuePtr](../../system.collections.generic/queueptr/)\<[SharedPtr](../sharedptr/)\<U\>\>\&) | Porovnává fronty ukazatelů. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Stack](../../system.collections.generic/stack/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Stack](../../system.collections.generic/stack/)\<U\>\>\&) | Porovnává zásobníky neukazatelů. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Stack](../../system.collections.generic/stack/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Stack](../../system.collections.generic/stack/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | Porovnává zásobníky ukazatelů. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, U\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, U\>\>\&) | Porovnává seřazené slovníky neukazatelových mapovacích typů. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&) | Porovnává seřazené slovníky ukazatelových mapovacích typů. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\&) | Porovnává seřazené slovníky různých typů. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K, U\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K, U\>\>\&) | Porovnává seřazené seznamy neukazatelových mapovacích typů. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&) | Porovnává seřazené seznamy ukazatelových mapovacích typů. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K1, U1\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K2, U2\>\>\&) | Porovnává seřazené seznamy různých typů. |
| static **bool** [AreEqual](./areequal/)(const [System::Collections::Specialized::StringCollectionPtr](../../system.collections.specialized/stringcollectionptr/)\&, const [System::Collections::Specialized::StringCollectionPtr](../../system.collections.specialized/stringcollectionptr/)\&) | Porovnává kolekce řetězců. |
| static **bool** [AreEqual](./areequal/)(const [System::SharedPtr](../sharedptr/)\<[SCG::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&, const [System::SharedPtr](../sharedptr/)\<[SCG::IEnumerable](../../system.collections.generic/ienumerable/)\<U\>\>\&) | Porovnává instance IEnumerable. |

## Viz také

* jmenný prostor [System](../)
* knihovna [Aspose.Slides](../../)