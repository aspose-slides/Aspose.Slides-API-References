---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, zda budou skryté snímky exportovány. Výchozí hodnota je false.
type: docs
weight: 27
url: /cs/aspose.slides.export/gifoptions/get_exporthiddenslides/
---
## GifOptions::get_ExportHiddenSlides() metoda

Určuje, zda budou skryté snímky exportovány. Výchozí hodnota je false.

```cpp
bool Aspose::Slides::Export::GifOptions::get_ExportHiddenSlides() override
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