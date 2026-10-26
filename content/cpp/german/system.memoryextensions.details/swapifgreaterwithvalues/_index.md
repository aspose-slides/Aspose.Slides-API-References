---
title: SwapIfGreaterWithValues()
second_title: Aspose.Slides für C++ API Referenz
description: Vertauscht Schlüssel-Wert-Paare, wenn die Vergleichsbedingung erfüllt ist.
type: docs
weight: 53
url: /de/system.memoryextensions.details/swapifgreaterwithvalues/
---
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) function


Vertauscht Schlüssel-Wert-Paare, wenn die Vergleichsbedingung erfüllt ist.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TKey | Der Typ der Schlüssel |
| TValue | Der Typ der Werte |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Der Span der Schlüssel |
| values | [Span](../../system/span/)\<TValue\>\& | Der Span der Werte |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) Funktion für Schlüssel |
| i | **int32_t** | Erster Index zum Vergleich |
| j | **int32_t** | Zweiter Index zum Vergleich |

## Siehe auch

* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions::Details](../)
* Bibliothek [Aspose.Slides](../../)