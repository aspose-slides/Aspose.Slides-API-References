---
title: Overlaps()
second_title: Aspose.Slides for C++ API Reference
description: Determines if two ReadOnlySpans overlap in memory without calculating offset.
type: docs
weight: 313
url: /system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Determines if two ReadOnlySpans overlap in memory without calculating offset.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The first span to check for overlap |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The second span to check for overlap |

### Return Value

true if the spans share any common memory locations, false otherwise

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Determines if a [Span](../../system/span/) and [ReadOnlySpan](../../system/readonlyspan/) overlap in memory without calculating offset.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The [Span](../../system/span/) to check for overlap |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The [ReadOnlySpan](../../system/readonlyspan/) to check for overlap |

### Return Value

true if the spans share any common memory locations, false otherwise

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) function


Determines if two ReadOnlySpans overlap in memory and calculates the offset.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The first span to check for overlap |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The second span to check for overlap |
| elementOffset | **int32_t**\& | Output parameter that receives the offset between spans if they overlap |

### Return Value

true if the spans share any common memory locations, false otherwise

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) function


Determines if a [Span](../../system/span/) and [ReadOnlySpan](../../system/readonlyspan/) overlap in memory and calculates the offset.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The [Span](../../system/span/) to check for overlap |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The [ReadOnlySpan](../../system/readonlyspan/) to check for overlap |
| elementOffset | **int32_t**\& | Output parameter that receives the offset between spans if they overlap |

### Return Value

true if the spans share any common memory locations, false otherwise

## See Also

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)