---
title: set_Sound()
second_title: Aspose.Slides for C++ API Referencia
description: Meghatározott beágyazott hang az effektushoz. Írja IAudio.
type: docs
weight: 183
url: /hu/aspose.slides.animation/ieffect/set_sound/
---
## IEffect::set_Sound(System::SharedPtr\<IAudio\>) metódus

Meghatározott beágyazott hang az effektushoz. Írja [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_Sound(System::SharedPtr<IAudio> value)=0
```

## Megjegyzések


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Lekéri a dia effektus sorozatát
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Kivonja az effektus hangot bájt tömbbe
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAudio](../../../aspose.slides/iaudio/)
* Osztály [IEffect](../)
* Névtér [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)