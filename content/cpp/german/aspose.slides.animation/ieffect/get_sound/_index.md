---
title: get_Sound()
second_title: Aspose.Slides für C++ API-Referenz
description: Definiert eingebetteten Sound für den Effekt. Lesen Sie IAudio.
type: docs
weight: 170
url: /de/aspose.slides.animation/ieffect/get_sound/
---
## IEffect::get_Sound() Methode


Definiert eingebetteten Sound für den Effekt. Lesen [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::Animation::IEffect::get_Sound()=0
```

## Anmerkungen



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Ermittelt die Effektsequenz für die Folie
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Extrahiert den Effekt-Sound als Byte-Array
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAudio](../../../aspose.slides/iaudio/)
* Klasse [IEffect](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)