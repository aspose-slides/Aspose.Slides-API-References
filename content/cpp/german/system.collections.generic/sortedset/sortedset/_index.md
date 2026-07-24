---
title: SortedSet()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine leere Menge.
type: docs
weight: 1
url: /de/system.collections.generic/sortedset/sortedset/
---
## SortedSet::SortedSet() Konstruktor

Erstellt eine leere Menge.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet()
```

## SortedSet::SortedSet(int) Konstruktor

Erstellt eine leere Menge mit der angegebenen Kapazität.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(int capacity)
```

## SortedSet::SortedSet(const SharedPtr\<IComparer\<T\>\>\&) Konstruktor

Erstellt eine leere Menge, die den angegebenen Gleichheitsvergleich verwendet.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IComparer<T>> &comparer)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) Objekt, das mit [SortedSet](../) verknüpft wird. |

## SortedSet::SortedSet(const SharedPtr\<IEnumerable\<T\>\>\&) Konstruktor

Erstellt [SortedSet](../) basierend auf enumerierbaren Werten.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IEnumerable<T>> &items)
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [SortedSet](../)
* Klasse [IComparer](../../icomparer/)
* Klasse [IEnumerable](../../ienumerable/)
* Namensraum [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)