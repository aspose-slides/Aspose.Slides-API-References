---
title: set_DisableFontLigatures()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in ett värde som indikerar om text renderas utan att använda ligaturer. När den är satt till true, kommer ligaturer att inaktiveras i den renderade utdata. Som standard är denna egenskap satt till false.
type: docs
weight: 105
url: /sv/aspose.slides.export/htmloptions/set_disablefontligatures/
---
## HtmlOptions::set_DisableFontLigatures(bool) metod

Ställer in ett värde som indikerar om text renderas utan att använda ligaturer. När den är satt till **true** kommer ligaturer att inaktiveras i den renderade utdata. Som standard är denna egenskap satt till **false**.

```cpp
void Aspose::Slides::Export::HtmlOptions::set_DisableFontLigatures(bool value) override
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