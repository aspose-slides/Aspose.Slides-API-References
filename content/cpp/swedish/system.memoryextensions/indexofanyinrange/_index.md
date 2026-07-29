---
title: IndexOfAnyInRange()
second_title: Aspose.Slides för C++ API-referens
description: Hittar indexet för det första elementet som ligger inom det angivna intervallet i en ReadOnlySpan<T>
type: docs
weight: 196
url: /sv/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Hittar indexet för det första elementet som ligger inom det angivna intervallet i en ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i intervallet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Intervallet att söka i |
| lowInclusive | const T\& | Den nedre gränsen för intervallet (inkluderande) |
| highInclusive | const T\& | Den övre gränsen för intervallet (inkluderande) |

### Returvärde

Det nollbaserade indexet för det första elementet inom intervallet, eller -1 om det inte hittas

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) function

Hittar indexet för det första elementet som ligger inom det angivna intervallet i en Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i intervallet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Intervallet att söka i |
| lowInclusive | const T\& | Den nedre gränsen för intervallet (inkluderande) |
| highInclusive | const T\& | Den övre gränsen för intervallet (inkluderande) |

### Returvärde

Det nollbaserade indexet för det första elementet inom intervallet, eller -1 om det inte hittas

## Se även

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)