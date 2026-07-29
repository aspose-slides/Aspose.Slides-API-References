---
title: IndexOf()
second_title: Aspose.Slides för C++ API-referens
description: Hittar index för ett ReadOnlySpan<T>-värde i ett annat ReadOnlySpan<T>
type: docs
weight: 144
url: /sv/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funktion

Hittar index för ett ReadOnlySpan<T>-värde i ett annat ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | The type of elements in the spans |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search for |

### Returvärde

The zero-based index of the first occurrence, or -1 if not found

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) funktion


Hittar index för ett enskilt värde i ett ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | The type of elements in the span |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value | const T\& | The value to search for |

### Returvärde

The zero-based index of the first occurrence, or -1 if not found

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Hittar index för ett ReadOnlySpan<T>-värde i ett Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | The type of elements in the spans |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search for |

### Returvärde

The zero-based index of the first occurrence, or -1 if not found

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) funktion


Hittar index för ett enskilt värde i ett Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | The type of elements in the span |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| value | const T\& | The value to search for |

### Returvärde

The zero-based index of the first occurrence, or -1 if not found

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) funktion


Hittar index för ett ReadOnlySpan<char16_t>-värde i ett ReadOnlySpan<char16_t> med StringComparison.

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The span to search in |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The value to search for |
| comparisonType | [StringComparison](../../system/stringcomparison/) | The string comparison type to use |

### Returvärde

The zero-based index of the first occurrence, or -1 if not found

## Se även

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)