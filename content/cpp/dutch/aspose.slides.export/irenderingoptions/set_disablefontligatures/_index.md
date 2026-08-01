---
title: set_DisableFontLigatures()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. Wanneer ingesteld op true, worden ligaturen uitgeschakeld in de gerenderde uitvoer. Standaard is deze eigenschap ingesteld op false.
type: docs
weight: 53
url: /nl/aspose.slides.export/irenderingoptions/set_disablefontligatures/
---
## IRenderingOptions::set_DisableFontLigatures(bool) methode


Stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. Wanneer ingesteld op **true**, worden ligaturen uitgeschakeld in de gerenderde uitvoer. Standaard is deze eigenschap ingesteld op **false**.

```cpp
virtual void Aspose::Slides::Export::IRenderingOptions::set_DisableFontLigatures(bool value)=0
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Schakel ligaturen uit bij het renderen van tekst

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## Zie ook

* Klasse [IRenderingOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)