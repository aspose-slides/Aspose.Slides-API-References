---
title: CompareTo()
second_title: Aspose.Slides C++ API referenciája
description: Összehasonlít két karaktertartományt a megadott karakterlánc-összehasonlítási szabályok szerint.
type: docs
weight: 404
url: /hu/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) függvény

Összehasonlít két karaktertartományt a megadott karakterlánc-összehasonlítási szabályok szerint.

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Az első karaktertartomány |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A második karaktertartomány |
| comparisonType | [StringComparison](../../system/stringcomparison/) | A végrehajtandó karakterlánc-összehasonlítás típusa |

### Visszatérési érték

Negatív érték, ha span < other, nulla, ha egyenlő, pozitív, ha span > other

## Lásd még

* Enum [StringComparison](../../system/stringcomparison/)
* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Névtere [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)