---
title: CompareTo()
second_title: Aspose.Slides for C++ API Reference
description: Compares two character spans with specified string comparison rules.
type: docs
weight: 40
url: /system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function


Compares two character spans with specified string comparison rules.

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The first character span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The second character span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | The type of string comparison to perform |

### Return Value

Negative value if span < other, zero if equal, positive if span > other

## See Also

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)