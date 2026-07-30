---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje, zda budou skryté snímky exportovány. Výchozí hodnota je false.
type: docs
weight: 40
url: /cs/aspose.slides.export/gifoptions/set_exporthiddenslides/
---
## GifOptions::set_ExportHiddenSlides(bool) metoda


Určuje, zda budou skryté snímky exportovány. Výchozí hodnota je false.

```cpp
void Aspose::Slides::Export::GifOptions::set_ExportHiddenSlides(bool value) override
```

## Poznámky



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Viz také

* Třída [GifOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)