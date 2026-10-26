---
title: get_DisableFontLigatures()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar ett värde som indikerar om text renderas utan att använda ligaturer. När den är satt till true, kommer ligaturer att inaktiveras i den renderade utdata. Som standard är denna egenskap satt till false.
type: docs
weight: 40
url: /sv/aspose.slides.export/irenderingoptions/get_disablefontligatures/
---
## IRenderingOptions::get_DisableFontLigatures() metod


Hämtar ett värde som indikerar om text renderas utan att använda ligaturer. När den är satt till **true**, ligaturer kommer att inaktiveras i den renderade utdata. Som standard är denna egenskap satt till **false**.

```cpp
virtual bool Aspose::Slides::Export::IRenderingOptions::get_DisableFontLigatures()=0
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Inaktivera ligaturer i textrendering

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## Se även

* Klass [IRenderingOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)