---
title: get_SufficientResolution()
second_title: Aspose.Slides C++ API referenciája
description: Visszaad egy értéket, amely meghatározza a PDF-dokumentumban lévő képek felbontását.
type: docs
weight: 352
url: /hu/aspose.slides.export/pdfoptions/get_sufficientresolution/
---
## PdfOptions::get_SufficientResolution() metódus


Returns a value determining resolution of images inside PDF document.

```cpp
float Aspose::Slides::Export::PdfOptions::get_SufficientResolution() override
```

## Megjegyzések


A tulajdonság hatással van a fájlméretre, az exportálási időre és a képminőségre.

Az alapértelmezett érték **96**.

Ennek a paraméternek a hatása néhány tényezőtől függ. Az algoritmus megpróbálja a legjobb kimeneti képméretet elérni a tulajdonság értéke, a forráskép mérete és a képkeret mérete alapján. Hasonló tulajdonságértékek használata ugyanazt az eredményt hozhatja. Ajánlott a 16 vagy 32 lépést használni a látható hatás eléréséhez.

Olvasás **float**. 

## Lásd még

* Osztály [PdfOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)