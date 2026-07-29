---
title: ContainsAny()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar om en skrivskyddad span innehåller något av två värden.
type: docs
weight: 53
url: /sv/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funktion

Kontrollerar om en skrivskyddad span innehåller något av två värden.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i span |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spanet att söka i |
| value0 | const T\& | Det första värdet att söka efter |
| value1 | const T\& | Det andra värdet att söka efter |

### Returvärde

true om något av värdena hittas i span, false annars

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) funktion

Kontrollerar om en skrivskyddad span innehåller något av tre värden.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i span |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spanet att söka i |
| value0 | const T\& | Det första värdet att söka efter |
| value1 | const T\& | Det andra värdet att söka efter |
| value2 | const T\& | Det tredje värdet att söka efter |

### Returvärde

true om något av värdena hittas i span, false annars

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) funktion


Kontrollerar om en muterbar span innehåller något av två värden.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i span |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Den muterbara spanen att söka i |
| value0 | const T\& | Det första värdet att söka efter |
| value1 | const T\& | Det andra värdet att söka efter |

### Returvärde

true om något av värdena hittas i span, false annars

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) funktion


Kontrollerar om en muterbar span innehåller något av tre värden.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i span |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Den muterbara spanen att söka i |
| value0 | const T\& | Det första värdet att söka efter |
| value1 | const T\& | Det andra värdet att söka efter |
| value2 | const T\& | Det tredje värdet att söka efter |

### Returvärde

true om något av värdena hittas i span, false annars

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Kontrollerar om en skrivskyddad span innehåller något värde från en annan span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spanarna |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spanet att söka i |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spanet med värden att söka efter |

### Returvärde

true om något värde från values hittas i span, false annars

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Kontrollerar om en muterbar span innehåller något värde från en skrivskyddad span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spanarna |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Den muterbara spanen att söka i |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Den skrivskyddade spanen med värden att söka efter |

### Returvärde

true om något värde från values hittas i span, false annars

## Se även

* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions](../)
* Bibliotek [Aspose.Slides](../../)