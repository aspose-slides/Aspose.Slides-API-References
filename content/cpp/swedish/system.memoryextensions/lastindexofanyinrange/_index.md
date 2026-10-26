---
title: LastIndexOfAnyInRange()
second_title: Aspose.Slides för C++ API-referens
description: Hittar den sista förekomsten av något element inom det angivna intervallet i en span.
type: docs
weight: 261
url: /sv/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funktion

Hittar den sista förekomsten av något element inom det angivna intervallet i en span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spanen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spanen att söka i |
| lowInclusive | const T\& | Den nedre gränsen för intervallet (inklusive) |
| highInclusive | const T\& | Den övre gränsen för intervallet (inklusive) |

### Returvärde

Det nollbaserade indexet för det sista elementet inom intervallet, eller -1 om det inte hittades

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) funktion

Hittar den sista förekomsten av något element inom det angivna intervallet i en modifierbar span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spanen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Spanen att söka i |
| lowInclusive | const T\& | Den nedre gränsen för intervallet (inklusive) |
| highInclusive | const T\& | Den övre gränsen för intervallet (inklusive) |

### Returvärde

Det nollbaserade indexet för det sista elementet inom intervallet, eller -1 om det inte hittades

## Se även

* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions](../)
* Bibliotek [Aspose.Slides](../../)