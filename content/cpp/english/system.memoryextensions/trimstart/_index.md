---
title: TrimStart()
second_title: Aspose.Slides for C++ API Reference
description: Trims specified element from the start of a typed span.
type: docs
weight: 482
url: /system.memoryextensions/trimstart/
---
## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const T\&) function


Trims specified element from the start of a typed span.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const T &trimElement)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to trim |
| trimElement | const T\& | The element to trim |

### Return Value

A new span with the specified element trimmed from the start

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const T\&) function


Trims specified element from the start of a mutable typed span.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const T &trimElement)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | The mutable span to trim |
| trimElement | const T\& | The element to trim |

### Return Value

A new span with the specified element trimmed from the start

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Trims specified elements from the start of a typed span.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to trim |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The elements to trim |

### Return Value

A new span with the specified elements trimmed from the start

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Trims specified elements from the start of a mutable typed span.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | The mutable span to trim |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The elements to trim |

### Return Value

A new span with the specified elements trimmed from the start

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&) function


Trims whitespace characters from the start of a character span.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The character span to trim |

### Return Value

A new span with whitespace trimmed from the start

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&) function


Trims whitespace characters from the start of a mutable character span.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | The mutable character span to trim |

### Return Value

A new span with whitespace trimmed from the start

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, char16_t) function


Trims specified character from the start of a character span.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The character span to trim |
| trimchar | char16_t | The character to trim |

### Return Value

A new span with the specified character trimmed from the start

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, char16_t) function


Trims specified character from the start of a mutable character span.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, char16_t trimchar)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | The mutable character span to trim |
| trimchar | char16_t | The character to trim |

### Return Value

A new span with the specified character trimmed from the start

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function


Trims specified characters from the start of a character span.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The character span to trim |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The characters to trim |

### Return Value

A new span with the specified characters trimmed from the start

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function


Trims specified characters from the start of a mutable character span.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | The mutable character span to trim |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The characters to trim |

### Return Value

A new span with the specified characters trimmed from the start

## See Also

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)