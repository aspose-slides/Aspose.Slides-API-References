---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides för C++ API-referens
description: Avgör om dolda bilder ska exporteras. Standardvärdet är false.
type: docs
weight: 27
url: /sv/aspose.slides.export/igifoptions/get_exporthiddenslides/
---
## IGifOptions::get_ExportHiddenSlides() metod


Avgör om dolda bilder ska exporteras. Standardvärdet är false.

```cpp
virtual bool Aspose::Slides::Export::IGifOptions::get_ExportHiddenSlides()=0
```

## Anmärkningar



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Se också

* Klass [IGifOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)