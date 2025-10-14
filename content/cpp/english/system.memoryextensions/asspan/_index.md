---
title: AsSpan()
second_title: Aspose.Slides for C++ API Reference
description: Creates a read-only span from a string.
type: docs
weight: 1
url: /system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) function


Creates a read-only span from a string.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | The source string. |
| start | **int32_t** | The starting index in the string. |
| length | **int32_t** | The length of the span. |

### Return Value

ReadOnlySpan<char16_t> spanning the specified portion of the string.

## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) function


Creates a span from an array.

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the array. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | The source array. |
| start | **int32_t** | The starting index in the array. |
| length | **int32_t** | The length of the span. |

### Return Value

Span<T> spanning the specified portion of the array.

## See Also

* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [String](../../system/string/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)