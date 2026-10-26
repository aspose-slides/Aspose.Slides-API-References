---
title: Heapify()
second_title: Aspose.Slides pro C++ API Reference
description: Udržuje vlastnost haldy pro páry klíč-hodnota.
type: docs
weight: 92
url: /cs/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) funkce

Udržuje vlastnost haldy pro páry klíč-hodnota.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TKey | Typ klíčů |
| TValue | Typ hodnot |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Rozsah klíčů v haldě |
| values | [Span](../../system/span/)\<TValue\>\& | Rozsah hodnot v haldě |
| n | **int32_t** | Velikost haldy |
| i | **int32_t** | [Index](../../system/index/) od kterého heapify |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) funkce pro klíče |

## Viz také

* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions::Details](../)
* Knihovna [Aspose.Slides](../../)