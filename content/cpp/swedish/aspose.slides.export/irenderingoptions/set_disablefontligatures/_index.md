---
title: set_DisableFontLigatures()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in ett värde som anger om text renderas utan att använda ligaturer. När den är inställd på true, kommer ligaturer att inaktiveras i den renderade utdata. Som standard är denna egenskap inställd på false.
type: docs
weight: 53
url: /sv/aspose.slides.export/irenderingoptions/set_disablefontligatures/
---
## IRenderingOptions::set_DisableFontLigatures(bool) metod

Ställer in ett värde som anger om text renderas utan att använda ligaturer. När den är inställd på **true** kommer ligaturer att inaktiveras i den renderade utdata. Som standard är denna egenskap inställd på **false**.

```cpp
virtual void Aspose::Slides::Export::IRenderingOptions::set_DisableFontLigatures(bool value)=0
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