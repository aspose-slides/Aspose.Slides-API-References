---
title: get_DisableFontLigatures()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar ett värde som indikerar om text renderas utan att använda ligaturer. När den är satt till true inaktiveras ligaturer i den renderade utdata. Som standard är denna egenskap satt till false.
type: docs
weight: 326
url: /sv/aspose.slides.export/svgoptions/get_disablefontligatures/
---
## SVGOptions::get_DisableFontLigatures() metod


Returnerar ett värde som indikerar om text renderas utan att använda ligaturer. När den är satt till **true** kommer ligaturer att inaktiveras i den renderade utdata. Som standard är denna egenskap satt till **false**.

```cpp
bool Aspose::Slides::Export::SVGOptions::get_DisableFontLigatures() override
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Inaktivera ligaturer i textrendering

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Se även

* Klass [SVGOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)