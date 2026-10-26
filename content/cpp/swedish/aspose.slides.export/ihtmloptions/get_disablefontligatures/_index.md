---
title: get_DisableFontLigatures()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar ett värde som anger om text renderas utan att använda ligaturer. När den är inställd på true, kommer ligaturer att inaktiveras i den renderade utskriften. Som standard är denna egenskap satt till false.
type: docs
weight: 183
url: /sv/aspose.slides.export/ihtmloptions/get_disablefontligatures/
---
## IHtmlOptions::get_DisableFontLigatures() metod

Hämtar ett värde som anger om text renderas utan att använda ligaturer. När den är inställd på **true** kommer ligaturer att inaktiveras i den renderade utskriften. Som standard är denna egenskap satt till **false**.

```cpp
virtual bool Aspose::Slides::Export::IHtmlOptions::get_DisableFontLigatures()=0
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

* Klass [IHtmlOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)