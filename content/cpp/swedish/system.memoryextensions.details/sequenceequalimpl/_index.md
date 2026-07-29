---
title: SequenceEqualImpl()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar om två spann är lika med start från angivna positioner.
type: docs
weight: 27
url: /sv/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) funktion

Kontrollerar om två spann är lika med start från angivna positioner.

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ av element i spann |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Första spannet |
| start | const **int32_t** | Startindex i första spannet |
| length | **int32_t** | Antal element att jämföra |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Andra spannet |

### Returvärde

true om de angivna intervallen är lika, false annars

## Se även

* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Namnrymd [System::MemoryExtensions::Details](../)
* Bibliotek [Aspose.Slides](../../)