---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides C++ API referencia
description: Megállapítja, hogy a rejtett diák exportálva lesznek-e. Az alapértelmezett érték false.
type: docs
weight: 27
url: /hu/aspose.slides.export/gifoptions/get_exporthiddenslides/
---
## GifOptions::get_ExportHiddenSlides() metódus

Meghatározza, hogy a rejtett diák exportálva lesznek-e. Az alapértelmezett érték false.

```cpp
bool Aspose::Slides::Export::GifOptions::get_ExportHiddenSlides() override
```

## Megjegyzések


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```


## Lásd még

* Osztály [GifOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)