---
title: SwapIfGreaterWithValues()
second_title: Aspose.Slides voor C++ API-referentie
description: Wisselt sleutel-waarde-paren uit als aan de vergelijkingsvoorwaarde wordt voldaan.
type: docs
weight: 53
url: /nl/system.memoryextensions.details/swapifgreaterwithvalues/
---
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) functie

Wisselt sleutel-waarde-paren uit als aan de vergelijkingsvoorwaarde wordt voldaan.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TKey | Het type sleutels |
| TValue | Het type waarden |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Het bereik van sleutels |
| values | [Span](../../system/span/)\<TValue\>\& | Het bereik van waarden |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) functie voor sleutels |
| i | **int32_t** | Eerste index om te vergelijken |
| j | **int32_t** | Tweede index om te vergelijken |

## Zie ook

* Klasse [Span](../../system/span/)
* Naamruimte [System::MemoryExtensions::Details](../)
* Bibliotheek [Aspose.Slides](../../)