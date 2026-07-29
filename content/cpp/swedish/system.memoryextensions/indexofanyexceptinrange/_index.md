---
title: IndexOfAnyExceptInRange()
second_title: Aspose.Slides för C++ API-referens
description: Hittar index för det första elementet som ligger utanför det angivna intervallet i en ReadOnlySpan<T>
type: docs
weight: 183
url: /sv/system.memoryextensions/indexofanyexceptinrange/
---
## System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Hittar index för det första elementet som ligger utanför det angivna intervallet i en ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i intervallet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Intervallet att söka i |
| lowInclusive | const T\& | Det nedre gränsvärdet för intervallet (inkluderande) |
| highInclusive | const T\& | Det övre gränsvärdet för intervallet (inkluderande) |

### Returvärde

Det nollbaserade indexet för det första elementet som ligger utanför intervallet, eller -1 om det inte hittas

## System::MemoryExtensions::IndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) function

Hittar index för det första elementet som ligger utanför det angivna intervallet i en Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i intervallet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Intervallet att söka i |
| lowInclusive | const T\& | Det nedre gränsvärdet för intervallet (inkluderande) |
| highInclusive | const T\& | Det övre gränsvärdet för intervallet (inkluderande) |

### Returvärde

Det nollbaserade indexet för det första elementet som ligger utanför intervallet, eller -1 om det inte hittas

## Se även

* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions](../)
* Bibliotek [Aspose.Slides](../../)