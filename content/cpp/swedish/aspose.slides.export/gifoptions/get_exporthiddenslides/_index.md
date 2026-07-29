---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides för C++ API-referens
description: Avgör om dolda bilder ska exporteras. Standardvärdet är false.
type: docs
weight: 27
url: /sv/aspose.slides.export/gifoptions/get_exporthiddenslides/
---
## GifOptions::get_ExportHiddenSlides() metod


Avgör om dolda bilder ska exporteras. Standardvärdet är false.

```cpp
bool Aspose::Slides::Export::GifOptions::get_ExportHiddenSlides() override
```

## Anmärkningar



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Se också

* Klass [GifOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)