---
title: PickPivotAndPartition()
second_title: Aspose.Slides dla C++ - Odniesienie API
description: Wybiera pivot i dzieli pary klucz-wartość dla quicksorta.
type: docs
weight: 105
url: /pl/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) funkcja

Wybiera pivot i dzieli pary klucz-wartość dla quicksorta.

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TKey | Typ kluczy |
| TValue | Typ wartości |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Zakres kluczy do podzielenia |
| values | [Span](../../system/span/)\<TValue\>\& | Zakres wartości do podzielenia |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) funkcja dla kluczy |

### Wartość zwracana

Indeks pivot po podziale

## Zobacz także

* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions::Details](../)
* Biblioteka [Aspose.Slides](../../)