---
title: StartsWith()
second_title: Aspose.Slides for C++ API Reference
description: Checks if the span starts with the specified value.
type: docs
weight: 391
url: /system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) function


Checks if the span starts with the specified value.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check |
| value | const T\& | The value to check for at the beginning of the span |

### Return Value

true if the span starts with the value, false otherwise

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) function


Checks if a string span starts with the specified character array.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | The string span to check |
| val | const char16_t * | The character array to check for at the beginning |

### Return Value

true if the span starts with the character array, false otherwise

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Checks if the span starts with the specified value span.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span containing values to check for at the beginning |

### Return Value

true if the span starts with the value span, false otherwise

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Checks if the mutable span starts with the specified read-only value span.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to check |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The read-only span containing values to check for |

### Return Value

true if the span starts with the value span, false otherwise

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) function


Checks if the read-only span starts with the specified mutable value span.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The read-only span to check |
| value | const [Span](../../system/span/)\<T\>\& | The mutable span containing values to check for |

### Return Value

true if the span starts with the value span, false otherwise

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function


Checks if the character span starts with the specified value span using string comparison.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The character span to check |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The character span containing values to check for |
| comparisonType | [StringComparison](../../system/stringcomparison/) | The type of string comparison to perform |

### Return Value

true if the span starts with the value span, false otherwise

## See Also

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [String](../../system/string/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)