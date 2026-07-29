---
title: ContainsAnyExceptInRange()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar om en skrivskyddad span innehåller något element utanför det angivna intervallet.
type: docs
weight: 79
url: /sv/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funktion


Kontrollerar om en skrivskyddad span innehåller något element utanför det angivna intervallet.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på elementen i spanen (måste vara jämförbara) |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spanen att söka i |
| lowInclusive | const T\& | Nedre gräns (inklusive) |
| highInclusive | const T\& | Övre gräns (inklusive) |

### Returvärde

true om något element utanför intervallet hittas, false annars

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) funktion


Kontrollerar om en modifierbar span innehåller något element utanför det angivna intervallet.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på elementen i spanen (måste vara jämförbara) |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Den modifierbara spanen att söka i |
| lowInclusive | const T\& | Nedre gräns (inklusive) |
| highInclusive | const T\& | Övre gräns (inklusive) |

### Returvärde

true om något element utanför intervallet hittas, false annars

## Se även

* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions](../)
* Bibliotek [Aspose.Slides](../../)