---
title: set_Sound()
second_title: Aspose.Slides for C++ API referenciája
description: Az effektushoz beágyazott hangot definiál. Írja IAudio.
type: docs
weight: 183
url: /hu/aspose.slides.animation/effect/set_sound/
---
## Effect::set_Sound(System::SharedPtr\<IAudio\>) metódus


Az effektushoz beágyazott hangot definiálja. Írja [IAudio](../../../aspose.slides/iaudio/).

```cpp
void Aspose::Slides::Animation::Effect::set_Sound(System::SharedPtr<IAudio> value) override
```

## Megjegyzések



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Lekéri a dián lévő hatások sorozatát
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Kibontja a hatás hangját bájt tömbként
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```




## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAudio](../../../aspose.slides/iaudio/)
* Osztály [Effect](../)
* Névtér [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)