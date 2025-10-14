---
title: ContainsAnyInRange()
second_title: Aspose.Slides for C++ API Reference
description: Checks if a read-only span contains any element within the specified range.
type: docs
weight: 105
url: /system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function


Checks if a read-only span contains any element within the specified range.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span (must be comparable) |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| lowInclusive | const T\& | The lower bound (inclusive) |
| highInclusive | const T\& | The upper bound (inclusive) |

### Return Value

true if any element within the range is found, false otherwise

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) function


Checks if a mutable span contains any element within the specified range.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span (must be comparable) |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to search in |
| lowInclusive | const T\& | The lower bound (inclusive) |
| highInclusive | const T\& | The upper bound (inclusive) |

### Return Value

true if any element within the range is found, false otherwise

## See Also

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)