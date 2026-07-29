---
title: set_DisableFontLigatures()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in ett värde som indikerar om text renderas utan att använda ligaturer. När den är satt till true, kommer ligaturer att inaktiveras i den renderade utdata. Som standard är denna egenskap satt till false.
type: docs
weight: 53
url: /sv/aspose.slides.export/renderingoptions/set_disablefontligatures/
---
## RenderingOptions::set_DisableFontLigatures(bool) metod


Ställer in ett värde som indikerar om text renderas utan att använda ligaturer. När det är satt till **true**, kommer ligaturer att inaktiveras i den renderade utdata. Som standard är denna egenskap satt till **false**.

```cpp
void Aspose::Slides::Export::RenderingOptions::set_DisableFontLigatures(bool value) override
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

## Se också

* Klass [RenderingOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)