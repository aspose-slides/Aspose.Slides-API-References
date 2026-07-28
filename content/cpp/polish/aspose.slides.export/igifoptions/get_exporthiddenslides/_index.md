---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Określa, czy ukryte slajdy będą eksportowane. Domyślna wartość to false.
type: docs
weight: 27
url: /pl/aspose.slides.export/igifoptions/get_exporthiddenslides/
---
## IGifOptions::get_ExportHiddenSlides() metoda


Określa, czy ukryte slajdy będą eksportowane. Domyślna wartość to false.

```cpp
virtual bool Aspose::Slides::Export::IGifOptions::get_ExportHiddenSlides()=0
```

## Uwagi



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Zobacz także

* Klasa [IGifOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)