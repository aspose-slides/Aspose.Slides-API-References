---
title: Heapify()
second_title: Aspose.Slides för C++ API-referens
description: Upprätthåller heap-egenskapen för nyckel-värde-par.
type: docs
weight: 92
url: /sv/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) funktion

Upprätthåller heap-egenskapen för nyckel-värde-par.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TKey | Typen av nycklar |
| TValue | Typen av värden |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Spannet av nycklar i heapen |
| values | [Span](../../system/span/)\<TValue\>\& | Spannet av värden i heapen |
| n | **int32_t** | Storlek på heapen |
| i | **int32_t** | [Index](../../system/index/) att heapify från |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) funktion för nycklar |

## Se även

* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions::Details](../)
* Bibliotek [Aspose.Slides](../../)