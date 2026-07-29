---
title: set_DisableFontLigatures()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in ett värde som indikerar om text renderas utan att använda ligaturer. När den är satt till true kommer ligaturer att inaktiveras i den renderade utskriften. Som standard är denna egenskap satt till false.
type: docs
weight: 339
url: /sv/aspose.slides.export/svgoptions/set_disablefontligatures/
---
## SVGOptions::set_DisableFontLigatures(bool) metod

Ställer in ett värde som indikerar om text renderas utan att använda ligaturer. När den är inställd på **true** kommer ligaturer att inaktiveras i den renderade utskriften. Som standard är denna egenskap inställd på **false**.

```cpp
void Aspose::Slides::Export::SVGOptions::set_DisableFontLigatures(bool value) override
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