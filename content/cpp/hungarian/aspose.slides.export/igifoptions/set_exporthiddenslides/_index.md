---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides C++ API-referencia
description: Megállapítja, hogy a rejtett diák exportálva lesznek-e. Az alapértelmezett érték false.
type: docs
weight: 40
url: /hu/aspose.slides.export/igifoptions/set_exporthiddenslides/
---
## IGifOptions::set_ExportHiddenSlides(bool) metódus


Megállapítja, hogy a rejtett diák exportálva lesznek-e. Az alapértelmezett érték false.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_ExportHiddenSlides(bool value)=0
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