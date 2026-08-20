---
title: AsMemory()
second_title: Aspose.Slides for C++ API Reference
description: Casts a ReadOnlyMemory to mutable Memory.
type: docs
weight: 27
url: /system.runtime.interopservices/memorymarshal/asmemory/
---
## MemoryMarshal::AsMemory(const ReadOnlyMemory\<T\>\&) method


Casts a [ReadOnlyMemory](../../../system/readonlymemory/) to mutable [Memory](../../../system/memory/).

```cpp
template<typename T> static Memory<T> System::Runtime::InteropServices::MemoryMarshal::AsMemory(const ReadOnlyMemory<T> &memory)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the [ReadOnlyMemory](../../../system/readonlymemory/). |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| memory | const [ReadOnlyMemory](../../../system/readonlymemory/)\<T\>\& | The [ReadOnlyMemory](../../../system/readonlymemory/) to cast. |

### Return Value

A [Memory](../../../system/memory/) object that represents the same memory as the [ReadOnlyMemory](../../../system/readonlymemory/).

## See Also

* Class [Memory](../../../system/memory/)
* Class [ReadOnlyMemory](../../../system/readonlymemory/)
* Class [MemoryMarshal](../)
* Namespace [System::Runtime::InteropServices](../../)
* Library [Aspose.Slides](../../../)