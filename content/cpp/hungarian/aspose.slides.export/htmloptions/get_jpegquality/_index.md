---
title: get_JpegQuality()
second_title: Aspose.Slides C++ API referenciája
description: Visszaad egy értéket, amely meghatározza a JPEG képek minőségét a PDF-dokumentumban. Olvasandó uint8_t.
type: docs
weight: 144
url: /hu/aspose.slides.export/htmloptions/get_jpegquality/
---
## HtmlOptions::get_JpegQuality() metódus


Visszaad egy értéket, amely meghatározza a JPEG képek minőségét a PDF-dokumentumban. Olvasandó **uint8_t**.

```cpp
uint8_t Aspose::Slides::Export::HtmlOptions::get_JpegQuality() override
```

## Megjegyzések


Csak akkor hat, ha a dokumentum JPEG képeket tartalmaz.

Használja ezt a tulajdonságot a dokumentumban lévő képek minőségének lekérésére vagy beállítására PDF formátumba mentéskor. Az érték 0 és 100 között változhat, ahol a 0 a legrosszabb minőséget, de a maximális tömörítést jelenti, a 100 pedig a legjobb minőséget, de a minimális tömörítést.

Az alapértelmezett érték **95**.
## Lásd még

* Osztály [HtmlOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)