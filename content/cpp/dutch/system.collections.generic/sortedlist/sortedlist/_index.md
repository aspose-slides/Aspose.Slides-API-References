---
title: SortedList()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een lege lijst.
type: docs
weight: 1
url: /nl/system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() constructor

Maakt een lege lijst.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) constructor

Maakt een lege lijst.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) om te gebruiken. |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) constructor

Kopieerconstructor.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) om gegevens van te kopiëren. |

## SortedList::SortedList(const map_t\&) constructor

Kopieerconstructor.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Map om gegevens van te kopiëren. |

## SortedList::SortedList(int) constructor

Maakt een lege lijst.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| capacity | int | Aantal elementen om te reserveren. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [map_t](../map_t/)
* Class [SortedList](../)
* Class [IComparer](../../icomparer/)
* Class [IDictionary](../../idictionary/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)