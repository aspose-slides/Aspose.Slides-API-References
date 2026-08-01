---
title: SortedSet()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een lege set.
type: docs
weight: 1
url: /nl/system.collections.generic/sortedset/sortedset/
---
## SortedSet::SortedSet() constructor

Maakt een lege set.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet()
```

## SortedSet::SortedSet(int) constructor

Maakt een lege set met opgegeven capaciteit.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(int capacity)
```

## SortedSet::SortedSet(const SharedPtr\<IComparer\<T\>\>\&) constructor

Maakt een lege set die de opgegeven gelijkheidsvergelijker gebruikt.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IComparer<T>> &comparer)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) object om te associëren met [SortedSet](../). |

## SortedSet::SortedSet(const SharedPtr\<IEnumerable\<T\>\>\&) constructor

Maakt [SortedSet](../) op basis van doorenumerabele waarden.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IEnumerable<T>> &items)
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [SortedSet](../)
* Klasse [IComparer](../../icomparer/)
* Klasse [IEnumerable](../../ienumerable/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)