---
title: get_DisableFontLigatures()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar ett värde som anger om text renderas utan att använda ligaturer. När den är satt till true inaktiveras ligaturer i den renderade utskriften. Som standard är denna egenskap satt till false.
type: docs
weight: 131
url: /sv/aspose.slides.export/ihtml5options/get_disablefontligatures/
---
## IHtml5Options::get_DisableFontLigatures() metod

Hämtar ett värde som anger om text renderas utan att använda ligaturer. När den är inställd på **true** kommer ligaturer att inaktiveras i den renderade utskriften. Som standard är detta egenskap satt till **false**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_DisableFontLigatures()=0
```

## Anmärkningar

Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Inaktivera ligaturer i textrendering

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Se även

* Klass [IHtml5Options](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)