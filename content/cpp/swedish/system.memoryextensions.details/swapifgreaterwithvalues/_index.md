---
title: SwapIfGreaterWithValues()
second_title: Aspose.Slides för C++ API-referens
description: Byter plats på nyckel-värde-par om jämförelsevillkoret är uppfyllt.
type: docs
weight: 53
url: /sv/system.memoryextensions.details/swapifgreaterwithvalues/
---
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) funktion

Byter plats på nyckel-värde-par om jämförelsevillkoret är uppfyllt.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TKey | Typen av nycklar |
| TValue | Typen av värden |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Spannet av nycklar |
| values | [Span](../../system/span/)\<TValue\>\& | Spannet av värden |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) funktion för nycklar |
| i | **int32_t** | Första index att jämföra |
| j | **int32_t** | Andra index att jämföra |

## Se även

* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions::Details](../)
* Bibliotek [Aspose.Slides](../../)