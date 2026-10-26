---
title: get_DisableFontLigatures()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar ett värde som anger om text renderas utan att använda ligaturer. När den är satt till true, inaktiveras ligaturer i den renderade utdata. Som standard är denna egenskap satt till false.
type: docs
weight: 326
url: /sv/aspose.slides.export/isvgoptions/get_disablefontligatures/
---
## ISSVGOptions::get_DisableFontLigatures() metod


Hämtar ett värde som anger om text renderas utan att använda ligaturer. När den är satt till **true** kommer ligaturer att inaktiveras i den renderade utdata. Som standard är denna egendom satt till **false**.

```cpp
virtual bool Aspose::Slides::Export::ISVGOptions::get_DisableFontLigatures()=0
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

* Klass [ISVGOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)