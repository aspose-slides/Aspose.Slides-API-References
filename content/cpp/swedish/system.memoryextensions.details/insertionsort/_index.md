---
title: InsertionSort()
second_title: Aspose.Slides för C++ API-referens
description: Utför insättningssortering på nyckel-värdepar.
type: docs
weight: 66
url: /sv/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) funktion

Utför insättningssortering på nyckel-värdepar.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TKey | Typen av nycklar |
| TValue | Typen av värden |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Spannet av nycklar att sortera |
| values | [Span](../../system/span/)\<TValue\>\& | Spannet av värden att sortera |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) funktion för nycklar |

## Se även

* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions::Details](../)
* Bibliotek [Aspose.Slides](../../)