---
title: SwapIfGreaterWithValues()
second_title: Aspose.Slides pro C++ – reference API
description: Prohodí páry klíč-hodnota, pokud je splněna podmínka porovnání.
type: docs
weight: 53
url: /cs/system.memoryextensions.details/swapifgreaterwithvalues/
---
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) funkce


Prohodí páry klíč-hodnota, pokud je splněna podmínka porovnání.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TKey | Typ klíčů |
| TValue | Typ hodnot |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Rozsah klíčů |
| values | [Span](../../system/span/)\<TValue\>\& | Rozsah hodnot |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | funkce [Comparison](../../system/comparison/) pro klíče |
| i | **int32_t** | První index k porovnání |
| j | **int32_t** | Druhý index k porovnání |

## Viz také

* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions::Details](../)
* Knihovna [Aspose.Slides](../../)