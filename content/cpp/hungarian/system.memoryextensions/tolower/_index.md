---
title: ToLower()
second_title: Aspose.Slides C++ API referencia
description: A megadott kultúra használatával alakítja át a karaktereket kisbetűvé.
type: docs
weight: 443
url: /hu/system.memoryextensions/tolower/
---
## System::MemoryExtensions::ToLower(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) függvény

Átalakítja a karaktereket kisbetűvé a megadott kultúra használatával.

```cpp
int32_t System::MemoryExtensions::ToLower(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A konvertálandó forrás karakterspan |
| destination | [Span](../../system/span/)\<char16_t\>\& | A konvertált karakterek tárolására szolgáló célspan |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | A konvertáláshoz használandó kultúra (nullptr a jelenlegi kultúrához) |

### Visszatérési érték

A konvertált karakterek száma, vagy -1, ha a cél túl kicsi

## Lásd még

* Typedef [SharedPtr](../../system/sharedptr/)
* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Osztály [CultureInfo](../../system.globalization/cultureinfo/)
* Névtér [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)