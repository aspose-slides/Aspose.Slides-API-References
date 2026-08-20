---
title: AsBytes()
second_title: Aspose.Slides for C++ API Reference
description: Casts a Span of one primitive type T to Span of bytes.
type: docs
weight: 1
url: /system.runtime.interopservices/memorymarshal/asbytes/
---
## MemoryMarshal::AsBytes(const Span\<T\>\&) method


Casts a [Span](../../../system/span/) of one primitive type T to [Span](../../../system/span/) of bytes.

```cpp
template<typename T> static Span<uint8_t> System::Runtime::InteropServices::MemoryMarshal::AsBytes(const Span<T> &span)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../../system/span/)\<T\>\& | The span to cast. |

### Return Value

A span of bytes representing the same memory as the original span.

## See Also

* Class [Span](../../../system/span/)
* Class [MemoryMarshal](../)
* Namespace [System::Runtime::InteropServices](../../)
* Library [Aspose.Slides](../../../)