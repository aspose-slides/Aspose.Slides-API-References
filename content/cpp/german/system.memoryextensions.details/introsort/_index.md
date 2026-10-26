---
title: IntroSort()
second_title: Aspose.Slides für C++ API-Referenz
description: Interne Implementierung des Introsort-Algorithmus für Schlüssel-Wert-Paare.
type: docs
weight: 40
url: /de/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) Funktion

Interne Implementierung des Introsort-Algorithmus für Schlüssel-Wert-Paare.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TKey | The type of keys |
| TValue | The type of values |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Der Span der zu sortierenden Schlüssel |
| values | [Span](../../system/span/)\<TValue\>\& | Der Span der zu sortierenden Werte |
| depthLimit | **int32_t** | Maximale Rekursionstiefe, bevor zu Heapsort gewechselt wird |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) Funktion für Schlüssel |

## Siehe auch

* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions::Details](../)
* Bibliothek [Aspose.Slides](../../)