---
title: ToLower()
second_title: Aspose.Slides pro referenci API C++
description: Převádí znaky na malá písmena pomocí zadané kultury.
type: docs
weight: 443
url: /cs/system.memoryextensions/tolower/
---
## System::MemoryExtensions::ToLower(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) funkce


Převádí znaky na malá písmena pomocí zadané kultury.

```cpp
int32_t System::MemoryExtensions::ToLower(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Zdrojový rozsah znaků k převodu |
| destination | [Span](../../system/span/)\<char16_t\>\& | Cílový rozsah pro uložení převedených znaků |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | Kultura použitá pro převod (nullptr pro aktuální kulturu) |

### Návratová hodnota

Počet převedených znaků, nebo -1 pokud je cílový prostor příliš malý

## Viz také

* Typedef [SharedPtr](../../system/sharedptr/)
* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Třída [CultureInfo](../../system.globalization/cultureinfo/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)