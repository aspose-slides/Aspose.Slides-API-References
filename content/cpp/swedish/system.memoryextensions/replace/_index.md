---
title: Replace()
second_title: Aspose.Slides för C++ API-referens
description: Ersätter alla förekomster av ett värde med ett nytt värde i en Span.
type: docs
weight: 287
url: /sv/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) funktion

Ersätter alla förekomster av ett värde med ett nytt värde i en [Span](../../system/span/).

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Den span att modifiera på plats |
| oldValue | const T\& | Värdet att söka efter och ersätta |
| newValue | const T\& | Det nya värdet för att ersätta oldValue med |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) funktion

Kopierar element från källa till destination, och ersätter angivna värden under kopieringen.

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Den source [ReadOnlySpan](../../system/readonlyspan/) att kopiera från |
| destination | [Span](../../system/span/)\<T\>\& | Den destination [Span](../../system/span/) att kopiera till |
| oldValue | const T\& | Värdet att söka efter och ersätta under kopiering |
| newValue | const T\& | Det nya värdet för att ersätta oldValue med |

## Se också

* Klass [Span](../../system/span/)
* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Namnrymd [System::MemoryExtensions](../)
* Bibliotek [Aspose.Slides](../../)