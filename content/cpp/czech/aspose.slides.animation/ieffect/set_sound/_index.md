---
title: set_Sound()
second_title: Aspose.Slides pro C++ API Reference
description: Definuje vložený zvuk pro efekt. Zapište IAudio.
type: docs
weight: 183
url: /cs/aspose.slides.animation/ieffect/set_sound/
---
## IEffect::set_Sound(System::SharedPtr\<IAudio\>) metoda


Definuje vložený zvuk pro efekt. Zapište [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_Sound(System::SharedPtr<IAudio> value)=0
```

## Poznámky



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Získá sekvenci efektů pro snímek
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Extrahuje zvuk efektu do pole bajtů
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAudio](../../../aspose.slides/iaudio/)
* Třída [IEffect](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)