---
title: HeapSort()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Provádí řazení haldou na párech klíč-hodnota.
type: docs
weight: 79
url: /cs/system.memoryextensions.details/heapsort/
---
## System::MemoryExtensions::Details::HeapSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) funkce

Provádí řazení haldou na párech klíč-hodnota.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::HeapSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TKey | Typ klíčů |
| TValue | Typ hodnot |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Rozsah klíčů k řazení |
| values | [Span](../../system/span/)\<TValue\>\& | Rozsah hodnot k řazení |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) funkce pro klíče |

## Viz také

* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions::Details](../)
* Knihovna [Aspose.Slides](../../)