---
title: InsertionSort()
second_title: Aspose.Slides voor C++ API-referentie
description: Voert insertion sort uit op sleutel-waardeparen.
type: docs
weight: 66
url: /nl/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) functie

Voert insertion sort uit op sleutel-waardeparen.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TKey | Het type van sleutels |
| TValue | Het type van waarden |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | De span van sleutels om te sorteren |
| values | [Span](../../system/span/)\<TValue\>\& | De span van waarden om te sorteren |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) functie voor sleutels |

## Zie ook

* Klasse [Span](../../system/span/)
* Naamruimte [System::MemoryExtensions::Details](../)
* Bibliotheek [Aspose.Slides](../../)