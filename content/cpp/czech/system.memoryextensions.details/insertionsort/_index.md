---
title: InsertionSort()
second_title: Aspose.Slides pro C++ API Reference
description: Provádí vkládací řazení na párech klíč-hodnota.
type: docs
weight: 66
url: /cs/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) funkce

Provádí vkládací řazení na párech klíč-hodnota.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
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