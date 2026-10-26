---
title: BinarySearchImpl()
second_title: Aspose.Slides för C++ API-referens
description: Allmän implementation av binärsökning.
type: docs
weight: 118
url: /sv/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) funktion

Allmän implementation av binärsökning.

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ av element i span |
| TValue | Typ av värde att söka efter |
| TCompareFunc | Funktionstyp för jämförelse |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span att söka i |
| value | const TValue\& | Värdet att söka efter |
| compareFunc | TCompareFunc | Funktion som jämför värdet med span-elementet och returnerar **int32_t** (-1, 0, 1) |

### Returvärde

[Index](../../system/index/) av hittat element eller bitvis komplement av infogningspunkt

## Se även

* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Namnrymd [System::MemoryExtensions::Details](../)
* Bibliotek [Aspose.Slides](../../)