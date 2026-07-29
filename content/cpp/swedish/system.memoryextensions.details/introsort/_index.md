---
title: IntroSort()
second_title: Aspose.Slides för C++ API-referens
description: Intern implementering av introsort-algoritmen för nyckel-värde-par.
type: docs
weight: 40
url: /sv/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) funktion

Intern implementation av introsort-algoritmen för nyckel-värde-par.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TKey | Typen av nycklar |
| TValue | Typen av värden |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Omfånget av nycklar att sortera |
| values | [Span](../../system/span/)\<TValue\>\& | Omfånget av värden att sortera |
| depthLimit | **int32_t** | Maximalt rekursionsdjup innan byte till heapsort |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) funktion för nycklar |

## Se också

* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions::Details](../)
* Bibliotek [Aspose.Slides](../../)