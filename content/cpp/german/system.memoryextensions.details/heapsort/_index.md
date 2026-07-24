---
title: HeapSort()
second_title: Aspose.Slides für C++ API Referenz
description: Führt Heapsort bei Schlüssel-Wert-Paaren aus.
type: docs
weight: 79
url: /de/system.memoryextensions.details/heapsort/
---
## System::MemoryExtensions::Details::HeapSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) Funktion

Führt Heapsort bei Schlüssel-Wert-Paaren aus.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::HeapSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TKey | Der Typ der Schlüssel |
| TValue | Der Typ der Werte |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Der Span der Schlüssel zum Sortieren |
| values | [Span](../../system/span/)\<TValue\>\& | Der Span der Werte zum Sortieren |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) Funktion für Schlüssel |

## Siehe auch

* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions::Details](../)
* Bibliothek [Aspose.Slides](../../)