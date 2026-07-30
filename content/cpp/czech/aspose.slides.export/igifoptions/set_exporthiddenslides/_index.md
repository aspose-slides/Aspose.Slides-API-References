---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, zda budou skryté snímky exportovány. Výchozí hodnota je false.
type: docs
weight: 40
url: /cs/aspose.slides.export/igifoptions/set_exporthiddenslides/
---
## IGifOptions::set_ExportHiddenSlides(bool) metoda


Určuje, zda budou skryté snímky exportovány. Výchozí hodnota je false.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_ExportHiddenSlides(bool value)=0
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