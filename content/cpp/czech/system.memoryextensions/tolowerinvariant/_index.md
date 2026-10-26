---
title: ToLowerInvariant()
second_title: Aspose.Slides pro C++ API Reference
description: Převádí znaky na malá písmena pomocí invariantní kultury.
type: docs
weight: 456
url: /cs/system.memoryextensions/tolowerinvariant/
---
## System::MemoryExtensions::ToLowerInvariant(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&) function

Převede znaky na malá písmena pomocí invariantní kultury.

```cpp
int32_t System::MemoryExtensions::ToLowerInvariant(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Zdrojový úsek znaků k převodu |
| destination | [Span](../../system/span/)\<char16_t\>\& | Cílový úsek pro uložení převedených znaků |

### Návratová hodnota

Počet převedených znaků nebo -1, pokud je cílový úsek příliš malý

## Viz také

* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)