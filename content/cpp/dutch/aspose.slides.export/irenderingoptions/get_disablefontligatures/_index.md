---
title: get_DisableFontLigatures()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt een waarde op die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. Wanneer ingesteld op true, worden ligaturen uitgeschakeld in de gerenderde uitvoer. Standaard is deze eigenschap ingesteld op false.
type: docs
weight: 40
url: /nl/aspose.slides.export/irenderingoptions/get_disablefontligatures/
---
## IRenderingOptions::get_DisableFontLigatures() methode


Geeft een waarde die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. Wanneer ingesteld op **true**, worden ligaturen uitgeschakeld in de gerenderde uitvoer. Standaard is deze eigenschap ingesteld op **false**.

```cpp
virtual bool Aspose::Slides::Export::IRenderingOptions::get_DisableFontLigatures()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Ligaturen uitschakelen bij tekstweergave

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## Zie ook

* Klasse [IRenderingOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)