---
title: set_DisableFontLigatures()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in ett värde som anger om text renderas utan att använda ligaturer. När den är inställd på true, kommer ligaturer att vara inaktiverade i den renderade utdata. Som standard är denna egenskap inställd på false.
type: docs
weight: 144
url: /sv/aspose.slides.export/html5options/set_disablefontligatures/
---
## Html5Options::set_DisableFontLigatures(bool) metod

Ställer in ett värde som anger om text renderas utan att använda ligaturer. När den är inställd på **true** kommer ligaturer att vara inaktiverade i den renderade utdata. Som standard är denna egenskap inställd på **false**.

```cpp
void Aspose::Slides::Export::Html5Options::set_DisableFontLigatures(bool value) override
```

## Anmärkningar

Exempel:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Inaktivera ligaturer vid textrendering

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Se också

* Klass [Html5Options](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)