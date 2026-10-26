---
title: Count()
second_title: Aspose.Slides för C++ API-referens
description: Räknar förekomster av ett värde i en skrivskyddad span.
type: docs
weight: 118
url: /sv/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) funktion


Räknar förekomster av ett värde i en skrivskyddad span.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på elementen i span |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Det span som ska sökas i |
| value | const T\& | Värdet att räkna |

### Returvärde

Antalet gånger value förekommer i span

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Räknar förekomster av ett span inom ett annat skrivskyddat span.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på elementen i spannen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Det span som ska sökas i |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Det span vars förekomster ska räknas |

### Returvärde

Antalet gånger value förekommer i span

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) funktion


Räknar förekomster av ett enskilt värde i en Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på elementen i span |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Det span som ska sökas i |
| value | const T\& | Värdet vars förekomster ska räknas |

### Returvärde

Antalet förekomster av värdet i span

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Räknar förekomster av en ReadOnlySpan<T> i en Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på elementen i spannen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Det span som ska sökas i |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Det span som innehåller värden vars förekomster ska räknas |

### Returvärde

Antalet förekomster av värdespanen i målspannen

## Se även

* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions](../)
* Bibliotek [Aspose.Slides](../../)