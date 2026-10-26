---
title: HeapSort()
second_title: Aspose.Slides voor C++ API-referentie
description: Voert heap sort uit op sleutel-waardeparen.
type: docs
weight: 79
url: /nl/system.memoryextensions.details/heapsort/
---
## System::MemoryExtensions::Details::HeapSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) function


Voert heap sort uit op sleutel-waardeparen.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::HeapSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TKey | Het type sleutels |
| TValue | Het type waarden |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | De reeks sleutels om te sorteren |
| values | [Span](../../system/span/)\<TValue\>\& | De reeks waarden om te sorteren |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) functie voor sleutels |

## Zie ook

* Klasse [Span](../../system/span/)
* Namespace [System::MemoryExtensions::Details](../)
* Bibliotheek [Aspose.Slides](../../)