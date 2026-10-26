---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides C++ API Referenciája
description: Meghatározza, hogy a rejtett diák exportálva lesznek-e. Az alapértelmezett érték false.
type: docs
weight: 40
url: /hu/aspose.slides.export/gifoptions/set_exporthiddenslides/
---
## GifOptions::set_ExportHiddenSlides(bool) metódus

Meghatározza, hogy a rejtett diák exportálva lesznek-e. Az alapértelmezett érték false.

```cpp
void Aspose::Slides::Export::GifOptions::set_ExportHiddenSlides(bool value) override
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