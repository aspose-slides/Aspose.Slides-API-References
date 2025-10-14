---
title: ToLowerInvariant()
second_title: Aspose.Slides for C++ API Reference
description: Converts characters to lowercase using invariant culture.
type: docs
weight: 417
url: /system.memoryextensions/tolowerinvariant/
---
## System::MemoryExtensions::ToLowerInvariant(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&) function


Converts characters to lowercase using invariant culture.

```cpp
int32_t System::MemoryExtensions::ToLowerInvariant(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The source character span to convert |
| destination | [Span](../../system/span/)\<char16_t\>\& | The destination span to store converted characters |

### Return Value

Number of characters converted, or -1 if destination is too small

## See Also

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)