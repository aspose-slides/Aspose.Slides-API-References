---
title: HashSet()
second_title: Aspose.Slides für C++ API-Referenz
description: RTTI-Informationen.
type: docs
weight: 1
url: /de/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() Konstruktor

RTTI-Informationen.

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## Anmerkungen

Erstellt eine leere Menge. 
## HashSet::HashSet(int) Konstruktor

Erstellt eine leere Menge mit der angegebenen Kapazität.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) Konstruktor

Erstellt eine leere Menge, die den angegebenen EqualityComparer verwendet.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | [Comparer](../../comparer/) Objekt, das mit dem Hashset verknüpft werden soll. |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) Konstruktor

Erstellt ein Hashset basierend auf aufzählbaren Werten.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [HashSet](../)
* Klasse [IEqualityComparer](../../iequalitycomparer/)
* Klasse [IEnumerable](../../ienumerable/)
* Namensraum [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)