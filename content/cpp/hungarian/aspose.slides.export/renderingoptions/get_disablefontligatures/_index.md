---
title: get_DisableFontLigatures()
second_title: Aspose.Slides C++ API hivatkozás
description: Egy értéket ad vissza, amely azt jelzi, hogy a szöveget ligatúrák használata nélkül rendereli. Ha true értékre van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság false értékre van állítva.
type: docs
weight: 40
url: /hu/aspose.slides.export/renderingoptions/get_disablefontligatures/
---
## RenderingOptions::get_DisableFontLigatures() metódus

Egy értéket ad vissza, amely azt jelzi, hogy a szöveget ligatúrák használata nélkül rendereli. Ha **true**-ra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság **false**-ra van állítva.

```cpp
bool Aspose::Slides::Export::RenderingOptions::get_DisableFontLigatures() override
```

## Megjegyzések

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // A ligatúrák letiltása a szöveg renderelésében

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