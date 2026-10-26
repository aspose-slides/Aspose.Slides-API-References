---
title: InsertionSort()
second_title: Aspose.Slides für C++ API-Referenz
description: Führt Insertion-Sort auf Schlüssel-Wert-Paaren aus.
type: docs
weight: 66
url: /de/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) Funktion

Führt Insertion-Sort auf Schlüssel-Wert-Paaren aus.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TKey | Der Typ der Schlüssel |
| TValue | Der Typ der Werte |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Der zu sortierende Schlüssel-Span |
| values | [Span](../../system/span/)\<TValue\>\& | Der zu sortierende Werte-Span |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) Funktion für Schlüssel |

## Siehe auch

* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions::Details](../)
* Bibliothek [Aspose.Slides](../../)