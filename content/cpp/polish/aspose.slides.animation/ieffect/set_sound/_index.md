---
title: set_Sound()
second_title: Aspose.Slides dla C++ – odwołanie API
description: Zdefiniowano wbudowany dźwięk dla efektu. Zapisz IAudio.
type: docs
weight: 183
url: /pl/aspose.slides.animation/ieffect/set_sound/
---
## IEffect::set_Sound(System::SharedPtr\<IAudio\>) metoda

Zdefiniowano wbudowany dźwięk dla efektu. Napisz [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_Sound(System::SharedPtr<IAudio> value)=0
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

    // Wyodrębnia dźwięk efektu jako tablicę bajtów
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAudio](../../../aspose.slides/iaudio/)
* Klasa [IEffect](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)