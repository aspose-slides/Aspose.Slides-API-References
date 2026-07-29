---
title: TrimEnd()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort specificerat element från slutet på en typad span.
type: docs
weight: 378
url: /sv/system.memoryextensions/trimend/
---
## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const T\&) funktion


Tar bort specificerat element från slutet på en typad span.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const T &trimElement)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spanen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spanen att trimma |
| trimElement | const T\& | Elementet att trimma |

### Returvärde

En ny span med det specificerade elementet borttagen från slutet

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const T\&) funktion


Tar bort specificerat element från slutet på en muterbar typad span.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const T &trimElement)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spanen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Den muterbara spanen att trimma |
| trimElement | const T\& | Elementet att trimma |

### Returvärde

En ny span med det specificerade elementet borttagen från slutet

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Tar bort specificerade element från slutet på en typad span.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spanen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spanen att trimma |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Elementen att trimma |

### Returvärde

En ny span med de specificerade elementen borttagna från slutet

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Tar bort specificerade element från slutet på en muterbar typad span.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spanen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Den muterbara spanen att trimma |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Elementen att trimma |

### Returvärde

En ny span med de specificerade elementen borttagna från slutet

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&) funktion


Tar bort blankstegstecken från slutet på en tecken-span.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Tecken-spanen att trimma |

### Returvärde

En ny span med blanksteg borttagna från slutet

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&) funktion


Tar bort blankstegstecken från slutet på en muterbar tecken-span.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Den muterbara tecken-spanen att trimma |

### Returvärde

En ny span med blanksteg borttagna från slutet

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, char16_t) funktion


Tar bort specificerat tecken från slutet på en tecken-span.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Tecken-spanen att trimma |
| trimchar | char16_t | Tecknet att trimma |

### Returvärde

En ny span med det specificerade tecknet borttaget från slutet

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, char16_t) funktion


Tar bort specificerat tecken från slutet på en muterbar tecken-span.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, char16_t trimchar)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Den muterbara tecken-spanen att trimma |
| trimchar | char16_t | Tecknet att trimma |

### Returvärde

En ny span med det specificerade tecknet borttaget från slutet

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) funktion


Tar bort specificerade tecken från slutet på en tecken-span.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimChars)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Tecken-spanen att trimma |
| trimChars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Tecknen att trimma |

### Returvärde

En ny span med de specificerade tecknen borttagna från slutet

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) funktion


Tar bort specificerade tecken från slutet på en muterbar tecken-span.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Den muterbara tecken-spanen att trimma |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Tecknen att trimma |

### Returvärde

En ny span med de specificerade tecknen borttagna från slutet

## Se även

* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions](../)
* Bibliotek [Aspose.Slides](../../)