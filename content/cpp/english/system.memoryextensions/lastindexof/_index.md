---
title: LastIndexOf()
second_title: Aspose.Slides for C++ API Reference
description: Finds the last occurrence of a value within a span using specified string comparison.
type: docs
weight: 248
url: /system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function


Finds the last occurrence of a value within a span using specified string comparison.

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The span to search within |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The value to search for |
| comparisonType | [StringComparison](../../system/stringcomparison/) | The type of string comparison to perform |

### Return Value

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Finds the last occurrence of a sequence within a span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence to search for |

### Return Value

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) function


Finds the last occurrence of a single value within a span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value | const T\& | The value to search for |

### Return Value

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Finds the last occurrence of a sequence within a mutable span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence to search for |

### Return Value

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) function


Finds the last occurrence of a single value within a mutable span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value | const T\& | The value to search for |

### Return Value

The zero-based index of the last occurrence, or -1 if not found

## See Also

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)