---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides C++ API referencia
description: Meghatározza, hogy a rejtett diák exportálva lesznek-e. Az alapértelmezett érték false.
type: docs
weight: 27
url: /hu/aspose.slides.export/igifoptions/get_exporthiddenslides/
---
## IGifOptions::get_ExportHiddenSlides() metódus

Megállapítja, hogy a rejtett diák exportálva lesznek-e. Az alapértelmezett érték false.

```cpp
virtual bool Aspose::Slides::Export::IGifOptions::get_ExportHiddenSlides()=0
```

## Megjegyzések



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Lásd még

* Osztály [IGifOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)