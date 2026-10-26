---
title: get_DisableFontLigatures()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar ett värde som indikerar om text renderas utan att använda ligaturer. När den är satt till true inaktiveras ligaturer i den renderade utskriften. Som standard är denna egenskap satt till false.
type: docs
weight: 92
url: /sv/aspose.slides.export/htmloptions/get_disablefontligatures/
---
## HtmlOptions::get_DisableFontLigatures() metod

Hämtar ett värde som indikerar om text renderas utan att använda ligaturer. När den är satt till **true** kommer ligaturer att inaktiveras i den renderade utskriften. Som standard är denna egenskap satt till **false**.

```cpp
bool Aspose::Slides::Export::HtmlOptions::get_DisableFontLigatures() override
```

## Anmärkningar

Exempel:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Inaktivera ligaturer i textrendering

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Se även

* Klass [HtmlOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)