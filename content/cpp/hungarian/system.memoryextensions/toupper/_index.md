---
title: ToUpper()
second_title: Aspose.Slides for C++ API Referencia
description: A karaktereket a megadott kultúra használatával nagybetűvé konvertálja.
type: docs
weight: 469
url: /hu/system.memoryextensions/toupper/
---
## System::MemoryExtensions::ToUpper(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) függvény


A karaktereket a megadott kultúra használatával nagybetűvé konvertálja.

```cpp
int32_t System::MemoryExtensions::ToUpper(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A konvertálandó forrás karakter span |
| destination | [Span](../../system/span/)\<char16_t\>\& | A konvertált karakterek tárolására szolgáló cél span |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | A konverzióhoz használandó kultúra (nullptr az aktuális kultúrához) |

### Visszatérési érték

A konvertált karakterek száma, vagy -1, ha a cél túl kicsi

## Lásd még

* Típusdefiníció [SharedPtr](../../system/sharedptr/)
* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Osztály [CultureInfo](../../system.globalization/cultureinfo/)
* Névtér [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)