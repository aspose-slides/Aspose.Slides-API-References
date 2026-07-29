---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om dolda bilder ska exporteras. Standardvärdet är falskt.
type: docs
weight: 40
url: /sv/aspose.slides.export/igifoptions/set_exporthiddenslides/
---
## IGifOptions::set_ExportHiddenSlides(bool) metod

Bestämmer om dolda bilder ska exporteras. Standardvärdet är falskt.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_ExportHiddenSlides(bool value)=0
```

## Anmärkningar



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Se även

* Klass [IGifOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)