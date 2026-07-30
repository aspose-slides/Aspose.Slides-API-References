---
title: set_Sound()
second_title: Riferimento API di Aspose.Slides per C++
description: Definisce il suono incorporato per l'effetto. Scrivi IAudio.
type: docs
weight: 183
url: /it/aspose.slides.animation/ieffect/set_sound/
---
## IEffect::set_Sound(System::SharedPtr\<IAudio\>) metodo


Definisce un suono incorporato per l'effetto. Scrivi [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_Sound(System::SharedPtr<IAudio> value)=0
```

## Osservazioni



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Ottiene la sequenza degli effetti per la diapositiva
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Estrae il suono dell'effetto in un array di byte
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAudio](../../../aspose.slides/iaudio/)
* Classe [IEffect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Libreria [Aspose.Slides](../../../)