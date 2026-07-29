---
title: HeapSort()
second_title: Aspose.Slides för C++ API-referens
description: Utför heap sort på nyckel-värde-par.
type: docs
weight: 79
url: /sv/system.memoryextensions.details/heapsort/
---
## System::MemoryExtensions::Details::HeapSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) funktion

Utför heap sort på nyckel-värde-par.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::HeapSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TKey | Typen av nycklar |
| TValue | Typen av värden |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Det spann av nycklar som ska sorteras |
| values | [Span](../../system/span/)\<TValue\>\& | Det spann av värden som ska sorteras |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) funktion för nycklar |

## Se även

* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions::Details](../)
* Bibliotek [Aspose.Slides](../../)