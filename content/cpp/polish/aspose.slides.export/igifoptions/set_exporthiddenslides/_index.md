---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides – referencja API C++
description: Określa, czy ukryte slajdy będą eksportowane. Domyślna wartość to false.
type: docs
weight: 40
url: /pl/aspose.slides.export/igifoptions/set_exporthiddenslides/
---
## IGifOptions::set_ExportHiddenSlides(bool) metoda


Określa, czy ukryte slajdy będą eksportowane. Domyślna wartość to false.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_ExportHiddenSlides(bool value)=0
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