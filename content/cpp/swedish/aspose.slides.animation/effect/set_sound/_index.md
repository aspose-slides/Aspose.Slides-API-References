---
title: set_Sound()
second_title: Aspose.Slides för C++ API-referens
description: Definierat inbäddat ljud för effekt. Skriv IAudio.
type: docs
weight: 183
url: /sv/aspose.slides.animation/effect/set_sound/
---
## Effect::set_Sound(System::SharedPtr\<IAudio\>) metod


Definierat inbäddat ljud för effekt. Skriv [IAudio](../../../aspose.slides/iaudio/).

```cpp
void Aspose::Slides::Animation::Effect::set_Sound(System::SharedPtr<IAudio> value) override
```

## Anmärkningar


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Hämtar sekvensen av effekter för bilden
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Extraherar effektens ljud i en bytearray
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```


## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IAudio](../../../aspose.slides/iaudio/)
* Klass [Effect](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)