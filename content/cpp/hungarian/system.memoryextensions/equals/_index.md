---
title: Equals()
second_title: Aspose.Slides C++ API referencia
description: Két ReadOnlySpan<char16_t>-t hasonlít össze a StringComparison használatával.
type: docs
weight: 417
url: /hu/system.memoryextensions/equals/
---
## System::MemoryExtensions::Equals(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) függvény

Két ReadOnlySpan<char16_t>-t hasonlít össze egyenlőség szerint a StringComparison használatával.

```cpp
bool System::MemoryExtensions::Equals(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```

### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Az első span a hasonlításhoz |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A második span a hasonlításhoz |
| comparisonType | [StringComparison](../../system/stringcomparison/) | A használandó karakterlánc-összehasonlítás típusa |

### Return Value

true, ha a spanok egyenlőek, false egyébként

## See Also

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)