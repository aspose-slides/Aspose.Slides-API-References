---
title: SwapIfGreaterWithValues()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Zamienia pary klucz-wartość, jeśli spełniony jest warunek porównania.
type: docs
weight: 53
url: /pl/system.memoryextensions.details/swapifgreaterwithvalues/
---
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) funkcja

Zamienia pary klucz-wartość, jeśli spełniony jest warunek porównania.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TKey | Typ kluczy |
| TValue | Typ wartości |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Zakres kluczy |
| values | [Span](../../system/span/)\<TValue\>\& | Zakres wartości |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) funkcja dla kluczy |
| i | **int32_t** | Pierwszy indeks do porównania |
| j | **int32_t** | Drugi indeks do porównania |

## Zobacz także

* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions::Details](../)
* Biblioteka [Aspose.Slides](../../)