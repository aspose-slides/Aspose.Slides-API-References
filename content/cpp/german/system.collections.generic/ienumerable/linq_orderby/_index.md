---
title: LINQ_OrderBy()
second_title: Aspose.Slides für C++ API-Referenz
description: Sortiert die Elemente einer Sequenz in aufsteigender Reihenfolge gemäß den von keySelector ausgewählten Schlüsselwerten.
type: docs
weight: 209
url: /de/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) Methode

Sortiert die Elemente einer Sequenz in aufsteigender Reihenfolge gemäß den von keySelector ausgewählten Schlüsselwerten.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| keySelector | Eine Funktion, die einen Schlüssel aus einem Element extrahiert. |

### Rückgabewert

Ein IOrderedEnumerable, dessen Elemente nach einem Schlüssel sortiert sind.

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) Methode

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Klasse [Func](../../../system/func/)
* Klasse [IEnumerable](../)
* Namensraum [System::Collections::Generic](../../)
* Bibliothek [Aspose.Slides](../../../)