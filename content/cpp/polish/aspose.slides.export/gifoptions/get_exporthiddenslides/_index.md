---
title: get_ExportHiddenSlides()
second_title: Referencja API Aspose.Slides dla C++
description: Określa, czy ukryte slajdy będą eksportowane. Domyślna wartość to false.
type: docs
weight: 27
url: /pl/aspose.slides.export/gifoptions/get_exporthiddenslides/
---
## GifOptions::get_ExportHiddenSlides() metoda


Określa, czy ukryte slajdy będą eksportowane. Domyślna wartość to false.

```cpp
bool Aspose::Slides::Export::GifOptions::get_ExportHiddenSlides() override
```

## Uwagi



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Zobacz także

* Klasa [GifOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)