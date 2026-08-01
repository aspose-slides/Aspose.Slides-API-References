---
title: get_Sound()
second_title: Aspose.Slides voor C++ API-referentie
description: Gedefinieerd ingebed geluid voor effect. Lees IAudio.
type: docs
weight: 170
url: /nl/aspose.slides.animation/ieffect/get_sound/
---
## IEffect::get_Sound() methode

Gedefinieerd ingebed geluid voor effect. Lees [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::Animation::IEffect::get_Sound()=0
```

## Opmerkingen

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Haalt de effectensequentie op voor de dia
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Extraheert het effectgeluid in een byte-array
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAudio](../../../aspose.slides/iaudio/)
* Klasse [IEffect](../)
* Naamruimte [Aspose::Slides::Animation](../../)
* Bibliotheek [Aspose.Slides](../../../)