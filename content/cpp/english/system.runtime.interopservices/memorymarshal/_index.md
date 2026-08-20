---
title: MemoryMarshal
second_title: Aspose.Slides for C++ API Reference
description: Provides memory marshalling implementation. For compatibility with translated code only, as no managed code is supported on C++ side. This is a static type with no instance services. You should never create instances of it by any means.
type: docs
weight: 27
url: /system.runtime.interopservices/memorymarshal/
---
## MemoryMarshal class


Provides memory marshalling implementation. For compatibility with translated code only, as no managed code is supported on C++ side. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class MemoryMarshal
```

## Methods

| Method | Description |
| --- | --- |
| static [Span](../../system/span/)\<**uint8_t**\> [AsBytes](./asbytes/)(const [Span](../../system/span/)\<T\>\&) | Casts a [Span](../../system/span/) of one primitive type T to [Span](../../system/span/) of bytes. |
| static [Memory](../../system/memory/)\<T\> [AsMemory](./asmemory/)(const [ReadOnlyMemory](../../system/readonlymemory/)\<T\>\&) | Casts a [ReadOnlyMemory](../../system/readonlymemory/) to mutable [Memory](../../system/memory/). |
| static [Span](../../system/span/)\<TTo\> [Cast](./cast/)(const [Span](../../system/span/)\<TFrom\>\&) | Casts a [Span](../../system/span/) of one primitive type TFrom to another primitive type TTo. |
| static T\& [GetReference](./getreference/)(const [Span](../../system/span/)\<T\>\&) | Gets a reference to the first element of the specified span. |
| static T\& [GetReference](./getreference/)(const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\&) | Gets a reference to the first element of the specified read-only span. |
## See Also

* Namespace [System::Runtime::InteropServices](../)
* Library [Aspose.Slides](../../)