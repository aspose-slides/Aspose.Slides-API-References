---
title: set_Sound()
second_title: Aspose.Slides für C++ API Referenz
description: Definiert den eingebetteten Sound für den Effekt. Schreiben IAudio.
type: docs
weight: 183
url: /de/aspose.slides.animation/effect/set_sound/
---
## Effect::set_Sound(System::SharedPtr\<IAudio\>) Methode


Definiert den eingebetteten Sound für den Effekt. Schreiben [IAudio](../../../aspose.slides/iaudio/).

```cpp
void Aspose::Slides::Animation::Effect::set_Sound(System::SharedPtr<IAudio> value) override
```

## Hinweise



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

    // Extrahiert den Effekt-Sound in ein Byte-Array
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```




## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAudio](../../../aspose.slides/iaudio/)
* Klasse [Effect](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)