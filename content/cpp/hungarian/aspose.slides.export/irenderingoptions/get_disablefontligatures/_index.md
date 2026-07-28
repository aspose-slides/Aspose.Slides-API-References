---
title: get_DisableFontLigatures()
second_title: Aspose.Slides a C++-hoz API referenciája
description: Egy értéket ad vissza, amely jelzi, hogy a szöveg ligatúrák használata nélkül van-e renderelve. Ha true értékre van állítva, a ligatúrák le lesznek tiltva a renderelt kimenetben. Alapértelmezés szerint ez a tulajdonság false értékre van beállítva.
type: docs
weight: 40
url: /hu/aspose.slides.export/irenderingoptions/get_disablefontligatures/
---
## IRenderingOptions::get_DisableFontLigatures() method

Egy értéket ad vissza, amely azt mutatja, hogy a szöveget ligatúrák használata nélkül renderelik. Ha **true** értékre van állítva, a ligatúrák le lesznek tiltva a renderelt kimenetben. Alapértelmezés szerint ez a tulajdonság **false** értékre van beállítva.

```cpp
virtual bool Aspose::Slides::Export::IRenderingOptions::get_DisableFontLigatures()=0
```

## Megjegyzések

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Ligatúrák letiltása a szöveg renderelésében

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## Lásd még

* Osztály [IRenderingOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)