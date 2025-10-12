---
title: IndexOfAnyInRange()
second_title: Aspose.Slides for C++ API Reference
description: Finds the index of the first element that is within the specified range in a ReadOnlySpan<T>
type: docs
weight: 222
url: /system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function


Finds the index of the first element that is within the specified range in a ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| lowInclusive | const T\& | The lower bound of the range (inclusive) |
| highInclusive | const T\& | The upper bound of the range (inclusive) |

### Return Value

The zero-based index of the first element within the range, or -1 if not found

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) function


Finds the index of the first element that is within the specified range in a Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| lowInclusive | const T\& | The lower bound of the range (inclusive) |
| highInclusive | const T\& | The upper bound of the range (inclusive) |

### Return Value

The zero-based index of the first element within the range, or -1 if not found

## See Also

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)