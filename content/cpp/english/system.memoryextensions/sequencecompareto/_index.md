---
title: SequenceCompareTo()
second_title: Aspose.Slides for C++ API Reference
description: Compares two ReadOnlySpans lexicographically.
type: docs
weight: 352
url: /system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Compares two ReadOnlySpans lexicographically.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The first span to compare |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The second span to compare |

### Return Value

-1 if span < other, 0 if span == other, 1 if span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Compares a [Span](../../system/span/) and [ReadOnlySpan](../../system/readonlyspan/) lexicographically.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The [Span](../../system/span/) to compare |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The [ReadOnlySpan](../../system/readonlyspan/) to compare |

### Return Value

-1 if span < other, 0 if span == other, 1 if span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) function


Compares a [ReadOnlySpan](../../system/readonlyspan/) and [Span](../../system/span/) lexicographically.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The [ReadOnlySpan](../../system/readonlyspan/) to compare |
| other | const [Span](../../system/span/)\<T\>\& | The [Span](../../system/span/) to compare |

### Return Value

-1 if span < other, 0 if span == other, 1 if span > other

## See Also

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)