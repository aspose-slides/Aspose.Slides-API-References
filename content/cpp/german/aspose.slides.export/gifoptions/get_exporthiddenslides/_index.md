---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob versteckte Folien exportiert werden. Der Standardwert ist false.
type: docs
weight: 27
url: /de/aspose.slides.export/gifoptions/get_exporthiddenslides/
---
## GifOptions::get_ExportHiddenSlides() Methode


Bestimmt, ob versteckte Folien exportiert werden. Der Standardwert ist false.

```cpp
bool Aspose::Slides::Export::GifOptions::get_ExportHiddenSlides() override
```

## Anmerkungen



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Siehe auch

* Klasse [GifOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)