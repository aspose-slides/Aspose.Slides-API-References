---
title: ToLower()
second_title: Aspose.Slides for C++ API Reference
description: Converts characters to lowercase using specified culture.
type: docs
weight: 404
url: /system.memoryextensions/tolower/
---
## System::MemoryExtensions::ToLower(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) function


Converts characters to lowercase using specified culture.

```cpp
int32_t System::MemoryExtensions::ToLower(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The source character span to convert |
| destination | [Span](../../system/span/)\<char16_t\>\& | The destination span to store converted characters |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | The culture to use for conversion (nullptr for current culture) |

### Return Value

Number of characters converted, or -1 if destination is too small

## See Also

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Class [CultureInfo](../../system.globalization/cultureinfo/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)