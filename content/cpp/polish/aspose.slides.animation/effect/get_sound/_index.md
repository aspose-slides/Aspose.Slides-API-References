---
title: get_Sound()
second_title: Aspose.Slides dla C++ Referencja API
description: Zdefiniowano osadzony dźwięk dla efektu. Przeczytaj IAudio.
type: docs
weight: 170
url: /pl/aspose.slides.animation/effect/get_sound/
---
## Effect::get_Sound() metoda


Zdefiniowano dźwięk osadzony dla efektu. Przeczytaj [IAudio](../../../aspose.slides/iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Animation::Effect::get_Sound() override
```

## Uwagi


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Pobiera sekwencję efektów dla slajdu
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Pobiera dźwięk efektu jako tablicę bajtów
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```




## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAudio](../../../aspose.slides/iaudio/)
* Klasa [Effect](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)