---
title: LastIndexOf()
second_title: Aspose.Slides för C++ API-referens
description: Hittar den sista förekomsten av en sekvens inom en span.
type: docs
weight: 209
url: /sv/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Hittar den sista förekomsten av en sekvens inom en span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spanen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spanen att söka i |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Sekvensen att söka efter |

### Returvärde

Det nollbaserade indexet för den sista förekomsten, eller -1 om den inte hittas

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) function

Hittar den sista förekomsten av ett enskilt värde inom en span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spanen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spanen att söka i |
| value | const T\& | Värdet att söka efter |

### Returvärde

Det nollbaserade indexet för den sista förekomsten, eller -1 om den inte hittas

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Hittar den sista förekomsten av en sekvens inom en muterbar span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spanen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Spanen att söka i |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Sekvensen att söka efter |

### Returvärde

Det nollbaserade indexet för den sista förekomsten, eller -1 om den inte hittas

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) function

Hittar den sista förekomsten av ett enskilt värde inom en muterbar span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spanen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Spanen att söka i |
| value | const T\& | Värdet att söka efter |

### Returvärde

Det nollbaserade indexet för den sista förekomsten, eller -1 om den inte hittas

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

Hittar den sista förekomsten av ett värde inom en span med angiven strängjämförelse.

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Spanen att söka i |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Värdet att söka efter |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Typen av strängjämförelse att utföra |

### Returvärde

Det nollbaserade indexet för den sista förekomsten, eller -1 om den inte hittas

## Se även

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)