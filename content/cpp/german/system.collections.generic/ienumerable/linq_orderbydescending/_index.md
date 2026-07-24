---
title: LINQ_OrderByDescending()
second_title: Aspose.Slides für C++ API-Referenz
description: Sortiert die Elemente einer Sequenz in absteigender Reihenfolge entsprechend den von keySelector ausgewählten Schlüsselwerten.
type: docs
weight: 222
url: /de/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) Methode

Sortiert die Elemente einer Sequenz in absteigender Reihenfolge entsprechend den von keySelector ausgewählten Schlüsselwerten.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| keySelector | Eine Funktion, um einen Schlüssel aus einem Element zu extrahieren. |

### Rückgabewert

Ein IOrderedEnumerable, dessen Elemente in absteigender Reihenfolge des Schlüssels sortiert sind.

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) Methode

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Klasse [Func](../../../system/func/)
* Klasse [IEnumerable](../)
* Namensraum [System::Collections::Generic](../../)
* Bibliothek [Aspose.Slides](../../../)