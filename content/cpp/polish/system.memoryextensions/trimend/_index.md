---
title: TrimEnd()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Usuwa określony element z końca spanu o określonym typie.
type: docs
weight: 378
url: /pl/system.memoryextensions/trimend/
---
## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const T\&) funkcja


Usuwa określony element z końca spanu.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const T &trimElement)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | The type of elements in the span |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to trim |
| trimElement | const T\& | The element to trim |

### Wartość zwracana

A new span with the specified element trimmed from the end

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const T\&) funkcja


Usuwa określony element z końca mutowalnego spanu.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const T &trimElement)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | The type of elements in the span |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | The mutable span to trim |
| trimElement | const T\& | The element to trim |

### Wartość zwracana

A new span with the specified element trimmed from the end

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja


Usuwa określone elementy z końca spanu.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | The type of elements in the span |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to trim |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The elements to trim |

### Wartość zwracana

A new span with the specified elements trimmed from the end

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja


Usuwa określone elementy z końca mutowalnego spanu.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | The type of elements in the span |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | The mutable span to trim |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The elements to trim |

### Wartość zwracana

A new span with the specified elements trimmed from the end

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&) funkcja


Usuwa białe znaki z końca spanu znaków.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The character span to trim |

### Wartość zwracana

A new span with whitespace trimmed from the end

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&) funkcja


Usuwa białe znaki z końca mutowalnego spanu znaków.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | The mutable character span to trim |

### Wartość zwracana

A new span with whitespace trimmed from the end

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, char16_t) funkcja


Usuwa określony znak z końca spanu znaków.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The character span to trim |
| trimchar | char16_t | The character to trim |

### Wartość zwracana

A new span with the specified character trimmed from the end

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, char16_t) funkcja


Usuwa określony znak z końca mutowalnego spanu znaków.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, char16_t trimchar)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | The mutable character span to trim |
| trimchar | char16_t | The character to trim |

### Wartość zwracana

A new span with the specified character trimmed from the end

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) funkcja


Usuwa określone znaki z końca spanu znaków.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimChars)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The character span to trim |
| trimChars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The characters to trim |

### Wartość zwracana

A new span with the specified characters trimmed from the end

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) funkcja


Usuwa określone znaki z końca mutowalnego spanu znaków.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | The mutable character span to trim |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The characters to trim |

### Wartość zwracana

A new span with the specified characters trimmed from the end

## Zobacz także

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)