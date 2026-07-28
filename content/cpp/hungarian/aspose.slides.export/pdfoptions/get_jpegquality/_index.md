---
title: get_JpegQuality()
second_title: Aspose.Slides for C++ API Referencia
description: Visszaad egy értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. Olvas uint8_t.
type: docs
weight: 222
url: /hu/aspose.slides.export/pdfoptions/get_jpegquality/
---
## PdfOptions::get_JpegQuality() metódus

Visszaad egy értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumon belül. Olvas **uint8_t**.

```cpp
uint8_t Aspose::Slides::Export::PdfOptions::get_JpegQuality() override
```

## Megjegyzések

Csak akkor van hatása, ha a dokumentum JPEG képeket tartalmaz.

Használja ezt a tulajdonságot a dokumentumon belüli képek minőségének lekérdezéséhez vagy beállításához PDF formátumban történő mentéskor. Az érték 0 és 100 között változhat, ahol a 0 a legrosszabb minőséget, de a legnagyobb tömörítést jelenti, a 100 pedig a legjobb minőséget, de a legkisebb tömörítést.

Az alapértelmezett érték **100**.

## Lásd még

* Osztály [PdfOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)