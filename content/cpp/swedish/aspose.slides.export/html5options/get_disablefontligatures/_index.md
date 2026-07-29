---
title: get_DisableFontLigatures()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett värde som indikerar om text renderas utan att använda ligaturer. När den är satt till true inaktiveras ligaturer i den renderade utskriften. Som standard är denna egenskap satt till false.
type: docs
weight: 131
url: /sv/aspose.slides.export/html5options/get_disablefontligatures/
---
## Html5Options::get_DisableFontLigatures() metod

Returnerar ett värde som anger om text renderas utan att använda ligaturer. När den är satt till **true**, ligaturer kommer att inaktiveras i den renderade utskriften. Som standard är detta egenskap satt till **false**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_DisableFontLigatures() override
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Inaktivera ligaturer i textrendering

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Se också

* Klass [Html5Options](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)