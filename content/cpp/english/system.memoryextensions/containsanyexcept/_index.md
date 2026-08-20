---
title: ContainsAnyExcept()
second_title: Aspose.Slides for C++ API Reference
description: Checks if a read-only span contains any element except three specified values.
type: docs
weight: 79
url: /system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function


Checks if a read-only span contains any element except three specified values.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |
| value2 | const T\& | The third value to exclude |

### Return Value

true if any element different from the specified values is found, false otherwise

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) function


Checks if a mutable span contains any element except three specified values.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to search in |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |
| value2 | const T\& | The third value to exclude |

### Return Value

true if any element different from the specified values is found, false otherwise

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function


Checks if a read-only span contains any element except two specified values.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |

### Return Value

true if any element different from the specified values is found, false otherwise

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) function


Checks if a mutable span contains any element except two specified values.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to search in |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |

### Return Value

true if any element different from the specified values is found, false otherwise

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) function


Checks if a read-only span contains any element except a specified value.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value | const T\& | The value to exclude |

### Return Value

true if any element different from the specified value is found, false otherwise

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) function


Checks if a mutable span contains any element except a specified value.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to search in |
| value | const T\& | The value to exclude |

### Return Value

true if any element different from the specified value is found, false otherwise

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Checks if a read-only span contains any element except those in another span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span of values to exclude |

### Return Value

true if any element not in values is found, false otherwise

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Checks if a mutable span contains any element except those in a read-only span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to search in |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The read-only span of values to exclude |

### Return Value

true if any element not in values is found, false otherwise

## See Also

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)