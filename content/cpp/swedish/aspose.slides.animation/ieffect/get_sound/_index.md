---
title: get_Sound()
second_title: Aspose.Slides för C++ API-referens
description: Definierat inbäddat ljud för effekt. Läs IAudio.
type: docs
weight: 170
url: /sv/aspose.slides.animation/ieffect/get_sound/
---
## IEffect::get_Sound() metod


Definierat inbäddat ljud för effekt. Läs [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::Animation::IEffect::get_Sound()=0
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

    // Extraherar effektens ljud i byte-array
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IAudio](../../../aspose.slides/iaudio/)
* Klass [IEffect](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)