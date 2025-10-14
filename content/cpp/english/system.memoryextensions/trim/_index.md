---
title: Trim()
second_title: Aspose.Slides for C++ API Reference
description: Trims specified element from both ends of a typed span.
type: docs
weight: 456
url: /system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) function


Trims specified element from both ends of a typed span.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to trim |
| trimElement | T | The element to trim |

### Return Value

A new span with the specified element trimmed from both ends

## System::MemoryExtensions::Trim(Span\<T\>\&, T) function


Trims specified element from both ends of a mutable typed span.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | The mutable span to trim |
| trimElement | T | The element to trim |

### Return Value

A new span with the specified element trimmed from both ends

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Trims specified elements from both ends of a typed span.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
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

A new span with the specified elements trimmed from both ends

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Trims specified elements from both ends of a mutable typed span.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
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

A new span with the specified elements trimmed from both ends

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) function


Trims whitespace characters from both ends of a character span.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The character span to trim |

### Return Value

A new span with whitespace trimmed from both ends

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) function


Trims whitespace characters from both ends of a mutable character span.

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | The mutable character span to trim |

### Return Value

A new span with whitespace trimmed from both ends

## See Also

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)