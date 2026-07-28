---
title: get_Sound()
second_title: Aspose.Slides for C++ API Referencia
description: Az effektushoz definiált beágyazott hang. Olvassa el az IAudio-t.
type: docs
weight: 170
url: /hu/aspose.slides.animation/ieffect/get_sound/
---
## IEffect::get_Sound() metódus


Az effektushoz definiált beágyazott hang. Olvassa el [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::Animation::IEffect::get_Sound()=0
```

## Megjegyzések



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Megkapja a dia effektus sorozatát
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Kivonja az effektus hangját bájt tömbbe
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAudio](../../../aspose.slides/iaudio/)
* Osztály [IEffect](../)
* Névtér [Aspose::Slides::Animation](../../)
* Könyvtár [Aspose.Slides](../../../)