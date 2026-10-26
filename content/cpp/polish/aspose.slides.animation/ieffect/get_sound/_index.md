---
title: get_Sound()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zdefiniowany wbudowany dźwięk dla efektu. Przeczytaj IAudio.
type: docs
weight: 170
url: /pl/aspose.slides.animation/ieffect/get_sound/
---
## IEffect::get_Sound() metoda


Zdefiniowano wbudowany dźwięk dla efektu. Przeczytaj [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::Animation::IEffect::get_Sound()=0
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

    // Ekstrahuje dźwięk efektu jako tablicę bajtów
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAudio](../../../aspose.slides/iaudio/)
* Klasa [IEffect](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)