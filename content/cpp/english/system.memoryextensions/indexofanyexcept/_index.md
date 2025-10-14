---
title: IndexOfAnyExcept()
second_title: Aspose.Slides for C++ API Reference
description: Finds the index of the first element that is not equal to the specified value in a ReadOnlySpan<T>
type: docs
weight: 196
url: /system.memoryextensions/indexofanyexcept/
---
## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) function


Finds the index of the first element that is not equal to the specified value in a ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value | const T\& | The value to exclude from the search |

### Return Value

The zero-based index of the first non-matching element, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function


Finds the index of the first element that is not equal to either of two specified values in a ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value0 | const T\& | The first value to exclude from the search |
| value1 | const T\& | The second value to exclude from the search |

### Return Value

The zero-based index of the first non-matching element, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function


Finds the index of the first element that is not equal to any of three specified values in a ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value0 | const T\& | The first value to exclude from the search |
| value1 | const T\& | The second value to exclude from the search |
| value2 | const T\& | The third value to exclude from the search |

### Return Value

The zero-based index of the first non-matching element, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&) function


Finds the index of the first element that is not equal to the specified value in a Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| value | const T\& | The value to exclude from the search |

### Return Value

The zero-based index of the first non-matching element, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) function


Finds the index of the first element that is not equal to either of two specified values in a Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| value0 | const T\& | The first value to exclude from the search |
| value1 | const T\& | The second value to exclude from the search |

### Return Value

The zero-based index of the first non-matching element, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) function


Finds the index of the first element that is not equal to any of three specified values in a Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| value0 | const T\& | The first value to exclude from the search |
| value1 | const T\& | The second value to exclude from the search |
| value2 | const T\& | The third value to exclude from the search |

### Return Value

The zero-based index of the first non-matching element, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Finds the index of the first element that is not equal to any value in a span of values.

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span containing values to exclude from the search |

### Return Value

The zero-based index of the first non-matching element, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Finds the index of the first element that is not equal to any value in a span of values in a Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span containing values to exclude from the search |

### Return Value

The zero-based index of the first non-matching element, or -1 if not found

## See Also

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)