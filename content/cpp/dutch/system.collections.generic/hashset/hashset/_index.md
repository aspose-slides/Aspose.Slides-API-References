---
title: HashSet()
second_title: Aspose.Slides voor C++ API-referentie
description: RTTI-informatie.
type: docs
weight: 1
url: /nl/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() constructor

RTTI-informatie.

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## Opmerkingen

Maakt een lege set. 

## HashSet::HashSet(int) constructor

Maakt een lege set met gespecificeerde capaciteit.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) constructor

Maakt een lege set die de opgegeven equality comparer gebruikt.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | [Comparer](../../comparer/) object om te associëren met de hashset. |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) constructor

Maakt hashset op basis van enumerateerbare waarden.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [HashSet](../)
* Klasse [IEqualityComparer](../../iequalitycomparer/)
* Klasse [IEnumerable](../../ienumerable/)
* Namespace [System::Collections::Generic](../../)
* Bibliotheek [Aspose.Slides](../../../)