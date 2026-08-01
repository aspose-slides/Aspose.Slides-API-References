---
title: Heapify()
second_title: Aspose.Slides voor C++ API-referentie
description: Behoudt de heap-eigenschap voor sleutel-waardeparen.
type: docs
weight: 92
url: /nl/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) functie

Behoudt de heap-eigenschap voor sleutel-waardeparen.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TKey | Het type sleutels |
| TValue | Het type waarden |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Het bereik van sleutels in de heap |
| values | [Span](../../system/span/)\<TValue\>\& | Het bereik van waarden in de heap |
| n | **int32_t** | Grootte van de heap |
| i | **int32_t** | [Index](../../system/index/) om te heapifyen vanaf |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) functie voor sleutels |

## Zie ook

* Klasse [Span](../../system/span/)
* Namespace [System::MemoryExtensions::Details](../)
* Bibliotheek [Aspose.Slides](../../)