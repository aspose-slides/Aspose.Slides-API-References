---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa, czy ukryte slajdy będą eksportowane. Domyślna wartość to false.
type: docs
weight: 40
url: /pl/aspose.slides.export/gifoptions/set_exporthiddenslides/
---
## GifOptions::set_ExportHiddenSlides(bool) metoda


Określa, czy ukryte slajdy będą eksportowane. Domyślna wartość to false.

```cpp
void Aspose::Slides::Export::GifOptions::set_ExportHiddenSlides(bool value) override
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