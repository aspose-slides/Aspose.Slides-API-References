---
title: PickPivotAndPartition()
second_title: Aspose.Slides för C++ API-referens
description: Väljer pivot och partitionerar nyckel-värdepar för snabbsortering.
type: docs
weight: 105
url: /sv/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) function


Väljer pivot och partitionerar nyckel-värdepar för snabbsortering.

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TKey | Typen av nycklar |
| TValue | Typen av värden |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Span av nycklar som ska partitioneras |
| values | [Span](../../system/span/)\<TValue\>\& | Span av värden som ska partitioneras |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) funktion för nycklar |

### Returvärde

Pivot-indexet efter partitionering

## Se även

* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions::Details](../)
* Bibliotek [Aspose.Slides](../../)