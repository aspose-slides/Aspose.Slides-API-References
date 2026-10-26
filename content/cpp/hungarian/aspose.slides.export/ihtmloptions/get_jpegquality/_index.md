---
title: get_JpegQuality()
second_title: Aspose.Slides for C++ API referencia
description: Visszaad egy értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. Olvasandó uint8_t.
type: docs
weight: 79
url: /hu/aspose.slides.export/ihtmloptions/get_jpegquality/
---
## IHtmlOptions::get_JpegQuality() metódus

Visszaad egy értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. Olvasandó **uint8_t**.

```cpp
virtual uint8_t Aspose::Slides::Export::IHtmlOptions::get_JpegQuality()=0
```

## Megjegyzés

Csak akkor van hatása, ha a dokumentum JPEG képeket tartalmaz.

Használja ezt a tulajdonságot a dokumentumban lévő képek minőségének lekérésére vagy beállítására PDF formátumban mentéskor. Az érték 0 és 100 között változhat, ahol a 0 a legrosszabb minőséget, de a legnagyobb tömörítést jelenti, a 100 pedig a legjobb minőséget, de a legkisebb tömörítést.

Az alapértelmezett érték **95**.

## Lásd még

* Osztály [IHtmlOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)