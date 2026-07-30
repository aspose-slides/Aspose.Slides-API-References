---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides pro referenci API C++
description: Určuje, zda budou skryté snímky exportovány. Výchozí hodnota je false.
type: docs
weight: 27
url: /cs/aspose.slides.export/igifoptions/get_exporthiddenslides/
---
## IGifOptions::get_ExportHiddenSlides() metoda


Určuje, zda budou skryté snímky exportovány. Výchozí hodnota je false.

```cpp
virtual bool Aspose::Slides::Export::IGifOptions::get_ExportHiddenSlides()=0
```

## Poznámky



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Viz také

* Třída [IGifOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)