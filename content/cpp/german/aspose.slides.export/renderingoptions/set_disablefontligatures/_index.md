---
title: set_DisableFontLigatures()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn er auf true gesetzt wird, werden Ligaturen in der gerenderten Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.
type: docs
weight: 53
url: /de/aspose.slides.export/renderingoptions/set_disablefontligatures/
---
## RenderingOptions::set_DisableFontLigatures(bool) Methode


Setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn er auf **true** gesetzt ist, werden Ligaturen in der gerenderten Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf **false** gesetzt.

```cpp
void Aspose::Slides::Export::RenderingOptions::set_DisableFontLigatures(bool value) override
```

## Hinweise


Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Ligaturen beim Rendern von Text deaktivieren

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## Siehe auch

* Klasse [RenderingOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)