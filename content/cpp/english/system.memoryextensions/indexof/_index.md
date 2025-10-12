---
title: IndexOf()
second_title: Aspose.Slides for C++ API Reference
description: Finds the index of a ReadOnlySpan<char16_t> value in a ReadOnlySpan<char16_t> with StringComparison.
type: docs
weight: 170
url: /system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function


Finds the index of a ReadOnlySpan<char16_t> value in a ReadOnlySpan<char16_t> with StringComparison.

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The span to search in |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The value to search for |
| comparisonType | [StringComparison](../../system/stringcomparison/) | The string comparison type to use |

### Return Value

The zero-based index of the first occurrence, or -1 if not found

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Finds the index of a ReadOnlySpan<T> value in another ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search for |

### Return Value

The zero-based index of the first occurrence, or -1 if not found

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) function


Finds the index of a single value in a ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value | const T\& | The value to search for |

### Return Value

The zero-based index of the first occurrence, or -1 if not found

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Finds the index of a ReadOnlySpan<T> value in a Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search for |

### Return Value

The zero-based index of the first occurrence, or -1 if not found

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) function


Finds the index of a single value in a Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| value | const T\& | The value to search for |

### Return Value

The zero-based index of the first occurrence, or -1 if not found

## See Also

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)