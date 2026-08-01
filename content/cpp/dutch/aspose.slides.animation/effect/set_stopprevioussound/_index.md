---
title: set_StopPreviousSound()
second_title: Aspose.Slides for C++ API-referentie
description: Dit attribuut specificeert of het animatie-effect het vorige geluid stopt. Schrijf bool.
type: docs
weight: 209
url: /nl/aspose.slides.animation/effect/set_stopprevioussound/
---
## Effect::set_StopPreviousSound(bool) methode

Dit attribuut specificeert of het animatie-effect het vorige geluid stopt. Schrijf **bool**.

```cpp
void Aspose::Slides::Animation::Effect::set_StopPreviousSound(bool value) override
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

* Klasse [Effect](../)
* Naamruimte [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)