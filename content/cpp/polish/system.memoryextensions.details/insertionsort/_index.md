---
title: InsertionSort()
second_title: Aspose.Slides dla C++ - referencja API
description: Wykonuje sortowanie przez wstawianie na parach klucz-wartość.
type: docs
weight: 66
url: /pl/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) funkcja

Wykonuje sortowanie przez wstawianie na parach klucz-wartość.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TKey | Typ kluczy |
| TValue | Typ wartości |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Zakres kluczy do posortowania |
| values | [Span](../../system/span/)\<TValue\>\& | Zakres wartości do posortowania |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) funkcja dla kluczy |

## Zobacz także

* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions::Details](../)
* Biblioteka [Aspose.Slides](../../)