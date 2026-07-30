---
title: PickPivotAndPartition()
second_title: Aspose.Slides pro C++ API Reference
description: Vybere pivot a rozdělí páry klíč-hodnota pro rychlé řazení.
type: docs
weight: 105
url: /cs/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) funkce

Vybere pivot a rozdělí páry klíč-hodnota pro rychlé řazení.

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TKey | Typ klíčů |
| TValue | Typ hodnot |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Rozsah klíčů k rozdělení |
| values | [Span](../../system/span/)\<TValue\>\& | Rozsah hodnot k rozdělení |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) funkce pro klíče |

### Návratová hodnota

Index pivotu po rozdělení

## Viz také

* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions::Details](../)
* Knihovna [Aspose.Slides](../../)