---
title: ToUpper()
second_title: Aspose.Slides pro referenci API C++
description: Převádí znaky na velká písmena pomocí určené kultury.
type: docs
weight: 469
url: /cs/system.memoryextensions/toupper/
---
## System::MemoryExtensions::ToUpper(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) funkce

Převádí znaky na velká písmena pomocí zadané kultury.

```cpp
int32_t System::MemoryExtensions::ToUpper(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Zdrojový source znakový span pro převod |
| destination | [Span](../../system/span/)\<char16_t\>\& | Cílový destination span pro uložení převedených znaků |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | Kultura používaná pro převod (nullptr pro aktuální kulturu) |

### Návratová hodnota

Počet převedených znaků, nebo -1 pokud je destination příliš malý

## Viz také

* Typedef [SharedPtr](../../system/sharedptr/)
* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Třída [CultureInfo](../../system.globalization/cultureinfo/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)