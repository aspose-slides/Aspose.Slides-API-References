---
title: Replace()
second_title: Aspose.Slides for C++ API Reference
description: Replaces all occurrences of a value with a new value in a Span.
type: docs
weight: 326
url: /system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) function


Replaces all occurrences of a value with a new value in a [Span](../../system/span/).

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | The span to modify in-place |
| oldValue | const T\& | The value to search for and replace |
| newValue | const T\& | The new value to replace oldValue with |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) function


Copies elements from source to destination, replacing specified values during copy.

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The source [ReadOnlySpan](../../system/readonlyspan/) to copy from |
| destination | [Span](../../system/span/)\<T\>\& | The destination [Span](../../system/span/) to copy to |
| oldValue | const T\& | The value to search for and replace during copying |
| newValue | const T\& | The new value to replace oldValue with |

## See Also

* Class [Span](../../system/span/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)