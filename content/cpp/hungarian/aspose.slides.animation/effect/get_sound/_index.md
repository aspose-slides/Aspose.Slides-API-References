---
title: get_Sound()
second_title: Aspose.Slides for C++ API referencia
description: Meghatározott beágyazott hang az effektushoz. Olvassa el IAudio.
type: docs
weight: 170
url: /hu/aspose.slides.animation/effect/get_sound/
---
## Effect::get_Sound() metódus


Meghatározott beágyazott hang az effektushoz. Olvassa el [IAudio](../../../aspose.slides/iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Animation::Effect::get_Sound() override
```

## Megjegyzések



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Lekéri a diához tartozó effektussorozatot
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Kivonja az effektus hangot bájt tömbként
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```




## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAudio](../../../aspose.slides/iaudio/)
* Osztály [Effect](../)
* Névterület [Aspose::Slides::Animation](../../)
* Könyvtár [Aspose.Slides](../../../)