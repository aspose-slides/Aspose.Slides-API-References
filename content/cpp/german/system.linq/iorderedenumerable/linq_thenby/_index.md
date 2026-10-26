---
title: LINQ_ThenBy()
second_title: Aspose.Slides für C++ API Referenz
description: Führt eine nachträgliche Sortierung der Elemente in einer Sequenz in aufsteigender Reihenfolge nach einem Schlüssel durch.
type: docs
weight: 27
url: /de/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) Methode


Führt eine nachträgliche Sortierung der Elemente in einer Sequenz in aufsteigender Reihenfolge nach einem Schlüssel durch.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Key | The type of the key returned by keySelector. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | A function to extract a key from each element. |

### Rückgabewert

[System::Linq::IOrderedEnumerable](../) dessen Elemente nach einem Schlüssel sortiert sind.

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) Methode




```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IOrderedEnumerable](../)
* Klasse [Func](../../../system/func/)
* Namensraum [System::Linq](../../)
* Bibliothek [Aspose.Slides](../../../)