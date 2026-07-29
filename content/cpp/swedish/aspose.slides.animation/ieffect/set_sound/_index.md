---
title: set_Sound()
second_title: Aspose.Slides för C++ API-referens
description: Definierat inbäddat ljud för effekt. Skriv IAudio.
type: docs
weight: 183
url: /sv/aspose.slides.animation/ieffect/set_sound/
---
## IEffect::set_Sound(System::SharedPtr\<IAudio\>) metod


Definierat inbäddat ljud för effekt. Skriv [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_Sound(System::SharedPtr<IAudio> value)=0
```

## Anmärkningar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Hämtar effektsekvensen för bilden
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Extraherar effektljudet till en bytearray
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IAudio](../../../aspose.slides/iaudio/)
* Klass [IEffect](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)