---
title: IntroSort()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Wewnętrzna implementacja algorytmu introsort dla par klucz-wartość.
type: docs
weight: 40
url: /pl/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) funkcja


Wewnętrzna implementacja algorytmu introsort dla par klucz-wartość.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
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
| depthLimit | **int32_t** | Maksymalna głębokość rekurencji przed przejściem na heapsort |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) funkcja dla kluczy |

## Zobacz także

* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions::Details](../)
* Biblioteka [Aspose.Slides](../../)