---
title: LastIndexOfAnyExceptInRange()
second_title: Aspose.Slides för C++ API-referens
description: Hittar den sista förekomsten av ett element som ligger utanför det angivna intervallet inom ett span.
type: docs
weight: 248
url: /sv/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funktion

Hittar den sista förekomsten av ett element som ligger utanför det angivna intervallet inom ett span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på elementen i spanet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spanet att söka i |
| lowInclusive | const T\& | Det undre gränsvärdet för intervallet (inkluderande) |
| highInclusive | const T\& | Det övre gränsvärdet för intervallet (inkluderande) |

### Returvärde

Det nollbaserade indexet för det sista elementet utanför intervallet, eller -1 om det inte hittas

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) funktion

Hittar den sista förekomsten av ett element som ligger utanför det angivna intervallet inom ett modifierbart span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på elementen i spanet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Spanet att söka i |
| lowInclusive | const T\& | Det undre gränsvärdet för intervallet (inkluderande) |
| highInclusive | const T\& | Det övre gränsvärdet för intervallet (inkluderande) |

### Returvärde

Det nollbaserade indexet för det sista elementet utanför intervallet, eller -1 om det inte hittas

## Se även

* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions](../)
* Bibliotek [Aspose.Slides](../../)