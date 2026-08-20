---
title: GetReference()
second_title: Aspose.Slides for C++ API Reference
description: Gets a reference to the first element of the specified span.
type: docs
weight: 40
url: /system.runtime.interopservices/memorymarshal/getreference/
---
## MemoryMarshal::GetReference(const Span\<T\>\&) method


Gets a reference to the first element of the specified span.

```cpp
template<typename T> static T & System::Runtime::InteropServices::MemoryMarshal::GetReference(const Span<T> &span)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../../system/span/)\<T\>\& | The span to access. |

### Return Value

A reference to the first element of the span.

## MemoryMarshal::GetReference(const ReadOnlySpan\<T\>\&) method


Gets a reference to the first element of the specified read-only span.

```cpp
template<typename T> static T & System::Runtime::InteropServices::MemoryMarshal::GetReference(const ReadOnlySpan<T> &span)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the read-only span. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../../system/readonlyspan/)\<T\>\& | The read-only span to access. |

### Return Value

A reference to the first element of the read-only span.

## See Also

* Class [Span](../../../system/span/)
* Class [MemoryMarshal](../)
* Class [ReadOnlySpan](../../../system/readonlyspan/)
* Namespace [System::Runtime::InteropServices](../../)
* Library [Aspose.Slides](../../../)