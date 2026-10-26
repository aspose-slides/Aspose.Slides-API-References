---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om dolda bilder ska exporteras. Standardvärdet är falskt.
type: docs
weight: 40
url: /sv/aspose.slides.export/gifoptions/set_exporthiddenslides/
---
## GifOptions::set_ExportHiddenSlides(bool) metod

Bestämmer om dolda bilder ska exporteras. Standardvärdet är falskt.

```cpp
void Aspose::Slides::Export::GifOptions::set_ExportHiddenSlides(bool value) override
```

## Anmärkningar

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Se även

* Klass [GifOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)