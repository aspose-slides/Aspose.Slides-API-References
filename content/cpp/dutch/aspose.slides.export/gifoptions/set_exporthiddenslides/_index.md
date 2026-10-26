---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of verborgen dia's worden geëxporteerd. De standaardwaarde is false.
type: docs
weight: 40
url: /nl/aspose.slides.export/gifoptions/set_exporthiddenslides/
---
## GifOptions::set_ExportHiddenSlides(bool) methode

Bepaalt of verborgen dia's worden geëxporteerd. De standaardwaarde is false.

```cpp
void Aspose::Slides::Export::GifOptions::set_ExportHiddenSlides(bool value) override
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
* Bibliotheek [Aspose.Slides](../../../)