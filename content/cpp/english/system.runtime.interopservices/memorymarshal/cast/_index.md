---
title: Cast()
second_title: Aspose.Slides for C++ API Reference
description: Casts a Span of one primitive type TFrom to another primitive type TTo.
type: docs
weight: 14
url: /system.runtime.interopservices/memorymarshal/cast/
---
## MemoryMarshal::Cast(const Span\<TFrom\>\&) method


Casts a [Span](../../../system/span/) of one primitive type TFrom to another primitive type TTo.

```cpp
template<typename TFrom,typename TTo> static Span<TTo> System::Runtime::InteropServices::MemoryMarshal::Cast(const Span<TFrom> &span)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TFrom | The source type of the span. |
| TTo | The target type of the span. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../../system/span/)\<TFrom\>\& | The span to cast. |

### Return Value

A span of the target type.

## See Also

* Class [Span](../../../system/span/)
* Class [MemoryMarshal](../)
* Namespace [System::Runtime::InteropServices](../../)
* Library [Aspose.Slides](../../../)