---
title: LastIndexOfAny()
second_title: Aspose.Slides för C++ API-referens
description: Hittar den sista förekomsten av något av tre angivna värden i ett span.
type: docs
weight: 222
url: /sv/system.memoryextensions/lastindexofany/
---
## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) funktion

Hittar den sista förekomsten av något av tre angivna värden i ett span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | The type of elements in the span |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |
| value2 | const T\& | The third value to search for |

### Returvärde

Det nollbaserade indexet för den sista förekomsten, eller -1 om den inte hittas

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) funktion

Hittar den sista förekomsten av något av tre angivna värden i ett modifierbart span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | The type of elements in the span |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |
| value2 | const T\& | The third value to search for |

### Returvärde

Det nollbaserade indexet för den sista förekomsten, eller -1 om den inte hittas

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funktion


Hittar den sista förekomsten av något av två angivna värden i ett span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | The type of elements in the span |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |

### Returvärde

Det nollbaserade indexet för den sista förekomsten, eller -1 om den inte hittas

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&) funktion


Hittar den sista förekomsten av något av två angivna värden i ett modifierbart span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | The type of elements in the span |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |

### Returvärde

Det nollbaserade indexet för den sista förekomsten, eller -1 om den inte hittas

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Hittar den sista förekomsten av något värde från en sekvens i ett span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | The type of elements in the span |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence of values to search for |

### Returvärde

Det nollbaserade indexet för den sista förekomsten, eller -1 om den inte hittas

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Hittar den sista förekomsten av något värde från en sekvens i ett modifierbart span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | The type of elements in the span |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence of values to search for |

### Returvärde

Det nollbaserade indexet för den sista förekomsten, eller -1 om den inte hittas

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const Span\<T\>\&) funktion


Hittar den sista förekomsten av något värde från en modifierbar sekvens i ett modifierbart span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const Span<T> &values)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | The type of elements in the span |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| values | const [Span](../../system/span/)\<T\>\& | The sequence of values to search for |

### Returvärde

Det nollbaserade indexet för den sista förekomsten, eller -1 om den inte hittas

## Se även

* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions](../)
* Bibliotek [Aspose.Slides](../../)