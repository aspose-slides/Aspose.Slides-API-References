---
title: set_DisableFontLigatures()
second_title: Aspose.Slides för C++ API-referens
description: Anger ett värde som visar om text renderas utan att använda ligaturer. När den är satt till true inaktiveras ligaturer i den renderade utskriften. Som standard är denna egenskap satt till false.
type: docs
weight: 196
url: /sv/aspose.slides.export/ihtmloptions/set_disablefontligatures/
---
## IHtmlOptions::set_DisableFontLigatures(bool) metod


Ställer in ett värde som anger om text renderas utan att använda ligaturer. När den är satt till **true** kommer ligaturer att inaktiveras i den renderade utdata. Som standard är detta egenskap satt till **false**.

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_DisableFontLigatures(bool value)=0
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Inaktivera ligaturer i textrendering

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Se också

* Klass [IHtmlOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)