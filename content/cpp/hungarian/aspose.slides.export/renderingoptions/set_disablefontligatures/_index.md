---
title: set_DisableFontLigatures()
second_title: Aspose.Slides C++ API referencia
description: Beállít egy értéket, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül kerül renderelésre. Ha **true**-ra van állítva, a ligatúrák le lesznek tiltva a renderelt kimenetben. Alapértelmezés szerint ez a tulajdonság **false**-ra van beállítva.
type: docs
weight: 53
url: /hu/aspose.slides.export/renderingoptions/set_disablefontligatures/
---
## RenderingOptions::set_DisableFontLigatures(bool) metódus


Beállít egy értéket, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül kerül renderelésre. Ha **true**-ra van állítva, a ligatúrák le lesznek tiltva a renderelt kimenetben. Alapértelmezés szerint ez a tulajdonság **false**-ra van beállítva.

```cpp
void Aspose::Slides::Export::RenderingOptions::set_DisableFontLigatures(bool value) override
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Ligatúrák letiltása a szöveg renderelésénél

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## Lásd még

* Osztály [RenderingOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)