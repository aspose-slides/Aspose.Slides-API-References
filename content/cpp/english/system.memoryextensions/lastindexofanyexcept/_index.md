---
title: LastIndexOfAnyExcept()
second_title: Aspose.Slides for C++ API Reference
description: Finds the last occurrence of any element except three specified values within a span.
type: docs
weight: 274
url: /system.memoryextensions/lastindexofanyexcept/
---
## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function


Finds the last occurrence of any element except three specified values within a span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |
| value2 | const T\& | The third value to exclude |

### Return Value

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) function


Finds the last occurrence of any element except three specified values within a mutable span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |
| value2 | const T\& | The third value to exclude |

### Return Value

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function


Finds the last occurrence of any element except two specified values within a span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |

### Return Value

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) function


Finds the last occurrence of any element except two specified values within a mutable span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |

### Return Value

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) function


Finds the last occurrence of any element except a specified value within a span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value | const T\& | The value to exclude |

### Return Value

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&) function


Finds the last occurrence of any element except a specified value within a mutable span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value | const T\& | The value to exclude |

### Return Value

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Finds the last occurrence of any element except values from a sequence within a span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence of values to exclude |

### Return Value

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Finds the last occurrence of any element except values from a sequence within a mutable span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence of values to exclude |

### Return Value

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const Span\<T\>\&) function


Finds the last occurrence of any element except values from a mutable sequence within a mutable span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const Span<T> &values)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| values | const [Span](../../system/span/)\<T\>\& | The sequence of values to exclude |

### Return Value

The zero-based index of the last non-excluded element, or -1 if not found

## See Also

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)