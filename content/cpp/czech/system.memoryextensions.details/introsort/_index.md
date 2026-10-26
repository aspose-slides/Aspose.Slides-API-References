---
title: IntroSort()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Interní implementace algoritmu introsort pro páry klíč-hodnota.
type: docs
weight: 40
url: /cs/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) funkce

Interní implementace algoritmu introsort pro páry klíč-hodnota.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TKey | Typ klíčů |
| TValue | Typ hodnot |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Rozsah klíčů k seřazení |
| values | [Span](../../system/span/)\<TValue\>\& | Rozsah hodnot k seřazení |
| depthLimit | **int32_t** | Maximální hloubka rekurze před přepnutím na heapsort |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) funkce pro klíče |

## Viz také

* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions::Details](../)
* Knihovna [Aspose.Slides](../../)