---
title: set_Sound()
second_title: Aspose.Slides dla C++ - referencja API
description: Zdefiniowano wbudowany dźwięk dla efektu. Zapisz IAudio.
type: docs
weight: 183
url: /pl/aspose.slides.animation/effect/set_sound/
---
## Effect::set_Sound(System::SharedPtr\<IAudio\>) metoda

Zdefiniowano wbudowany dźwięk dla efektu. Zapisz [IAudio](../../../aspose.slides/iaudio/).

```cpp
void Aspose::Slides::Animation::Effect::set_Sound(System::SharedPtr<IAudio> value) override
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

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IAudio](../../../aspose.slides/iaudio/)
* Klasa [Effect](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)