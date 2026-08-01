---
title: get_StopPreviousSound()
second_title: Aspose.Slides voor C++ API-referentie
description: Dit attribuut geeft aan of het animatie-effect het vorige geluid stopt. Lees bool.
type: docs
weight: 196
url: /nl/aspose.slides.animation/ieffect/get_stopprevioussound/
---
## IEffect::get_StopPreviousSound() methode


Dit attribuut geeft aan of het animatie-effect het vorige geluid stopt. Lees **bool**.

```cpp
virtual bool Aspose::Slides::Animation::IEffect::get_StopPreviousSound()=0
```

## Opmerkingen



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Haal het eerste effect van de eerste dia op.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Haal het eerste effect van de tweede dia op.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Verander het tweede effect Enhancements/Sound naar "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Zie ook

* Klasse [IEffect](../)
* Naamruimte [Aspose::Slides::Animation](../../)
* Bibliotheek [Aspose.Slides](../../../)