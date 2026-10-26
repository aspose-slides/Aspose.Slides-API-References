---
title: ContainsAnyExcept()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar om ett read-only span innehåller något element förutom tre angivna värden.
type: docs
weight: 66
url: /sv/system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) funktion


Kontrollerar om ett read-only-span innehåller något element förutom tre angivna värden.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på element i spannet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spannet att söka i |
| value0 | const T\& | Det första värdet att exkludera |
| value1 | const T\& | Det andra värdet att exkludera |
| value2 | const T\& | Det tredje värdet att exkludera |

### Returvärde

true om något element som skiljer sig från de angivna värdena hittas, false annars

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) funktion


Kontrollerar om ett mutabelt span innehåller något element förutom tre angivna värden.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på element i spannet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Det mutabla spannet att söka i |
| value0 | const T\& | Det första värdet att exkludera |
| value1 | const T\& | Det andra värdet att exkludera |
| value2 | const T\& | Det tredje värdet att exkludera |

### Returvärde

true om något element som skiljer sig från de angivna värdena hittas, false annars

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funktion


Kontrollerar om ett read-only-span innehåller något element förutom två angivna värden.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på element i spannet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spannet att söka i |
| value0 | const T\& | Det första värdet att exkludera |
| value1 | const T\& | Det andra värdet att exkludera |

### Returvärde

true om något element som skiljer sig från de angivna värdena hittas, false annars

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) funktion


Kontrollerar om ett mutabelt span innehåller något element förutom två angivna värden.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på element i spannet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Det mutabla spannet att söka i |
| value0 | const T\& | Det första värdet att exkludera |
| value1 | const T\& | Det andra värdet att exkludera |

### Returvärde

true om något element som skiljer sig från de angivna värdena hittas, false annars

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) funktion


Kontrollerar om ett read-only-span innehåller något element förutom ett angivet värde.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på element i spannet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spannet att söka i |
| value | const T\& | Värdet att exkludera |

### Returvärde

true om något element som skiljer sig från det angivna värdet hittas, false annars

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) funktion


Kontrollerar om ett mutabelt span innehåller något element förutom ett angivet värde.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på element i spannet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Det mutabla spannet att söka i |
| value | const T\& | Värdet att exkludera |

### Returvärde

true om något element som skiljer sig från det angivna värdet hittas, false annars

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Kontrollerar om ett read-only-span innehåller något element förutom de i ett annat span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på element i spannen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spannet att söka i |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spannet med värden att exkludera |

### Returvärde

true om något element som inte finns i values hittas, false annars

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Kontrollerar om ett mutabelt span innehåller något element förutom de i ett read-only-span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på element i spannen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Det mutabla spannet att söka i |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Det read-only-span med värden att exkludera |

### Returvärde

true om något element som inte finns i values hittas, false annars

## Se även

* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions](../)
* Bibliotek [Aspose.Slides](../../)