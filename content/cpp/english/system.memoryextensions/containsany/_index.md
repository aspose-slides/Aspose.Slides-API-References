---
title: ContainsAny()
second_title: Aspose.Slides for C++ API Reference
description: Checks if a read-only span contains any of two values.
type: docs
weight: 66
url: /system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function


Checks if a read-only span contains any of two values.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |

### Return Value

true if any of the values is found in span, false otherwise

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function


Checks if a read-only span contains any of three values.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |
| value2 | const T\& | The third value to search for |

### Return Value

true if any of the values is found in span, false otherwise

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) function


Checks if a mutable span contains any of two values.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to search in |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |

### Return Value

true if any of the values is found in span, false otherwise

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) function


Checks if a mutable span contains any of three values.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to search in |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |
| value2 | const T\& | The third value to search for |

### Return Value

true if any of the values is found in span, false otherwise

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Checks if a read-only span contains any value from another span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span of values to search for |

### Return Value

true if any value from values is found in span, false otherwise

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Checks if a mutable span contains any value from a read-only span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to search in |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The read-only span of values to search for |

### Return Value

true if any value from values is found in span, false otherwise

## See Also

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)