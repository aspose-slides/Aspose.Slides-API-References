---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of verborgen dia's worden geëxporteerd. De standaardwaarde is false.
type: docs
weight: 27
url: /nl/aspose.slides.export/gifoptions/get_exporthiddenslides/
---
## GifOptions::get_ExportHiddenSlides() methode


Bepaalt of verborgen dia's worden geëxporteerd. De standaardwaarde is false.

```cpp
bool Aspose::Slides::Export::GifOptions::get_ExportHiddenSlides() override
```

## Opmerkingen



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Zie ook

* Klasse [GifOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)