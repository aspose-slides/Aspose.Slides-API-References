---
title: Heapify()
second_title: Aspose.Slides für C++ API-Referenz
description: Erhält die Heap-Eigenschaft für Schlüssel-Wert-Paare.
type: docs
weight: 92
url: /de/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) Funktion

Erhält die Heap-Eigenschaft für Schlüssel-Wert-Paare.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TKey | Der Typ der Schlüssel |
| TValue | Der Typ der Werte |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Der Span der Schlüssel im Heap |
| values | [Span](../../system/span/)\<TValue\>\& | Der Span der Werte im Heap |
| n | **int32_t** | Größe des Heaps |
| i | **int32_t** | [Index](../../system/index/) zum heapify von |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) Funktion für Schlüssel |

## Siehe auch

* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions::Details](../)
* Bibliothek [Aspose.Slides](../../)