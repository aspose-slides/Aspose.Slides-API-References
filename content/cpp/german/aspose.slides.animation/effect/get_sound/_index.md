---
title: get_Sound()
second_title: Aspose.Slides für C++ API-Referenz
description: Definiert den eingebetteten Sound für den Effekt. Lesen Sie IAudio.
type: docs
weight: 170
url: /de/aspose.slides.animation/effect/get_sound/
---
## Effect::get_Sound() Methode


Definiert den eingebetteten Sound für den Effekt. Lesen Sie [IAudio](../../../aspose.slides/iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Animation::Effect::get_Sound() override
```

## Bemerkungen



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Holt die Effektsequenz für die Folie
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Extrahiert den Sound des Effekts in ein Byte-Array
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```




## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAudio](../../../aspose.slides/iaudio/)
* Klasse [Effect](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)