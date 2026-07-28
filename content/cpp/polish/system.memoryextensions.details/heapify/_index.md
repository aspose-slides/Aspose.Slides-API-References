---
title: Heapify()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Utrzymuje własność kopca dla par klucz-wartość.
type: docs
weight: 92
url: /pl/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) funkcja

Utrzymuje własność kopca dla par klucz-wartość.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TKey | Typ kluczy |
| TValue | Typ wartości |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Zakres kluczy w kopcu |
| values | [Span](../../system/span/)\<TValue\>\& | Zakres wartości w kopcu |
| n | **int32_t** | Rozmiar kopca |
| i | **int32_t** | [Index](../../system/index/) do heapify od |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) funkcja dla kluczy |

## Zobacz także

* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions::Details](../)
* Biblioteka [Aspose.Slides](../../)