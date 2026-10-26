---
title: get_StopPreviousSound()
second_title: Aspose.Slides für C++ API Referenz
description: Dieses Attribut gibt an, ob der Animationseffekt den vorherigen Sound stoppt. Lesen bool.
type: docs
weight: 196
url: /de/aspose.slides.animation/ieffect/get_stopprevioussound/
---
## IEffect::get_StopPreviousSound() Methode

Dieses Attribut gibt an, ob der Animationseffekt den vorherigen Sound stoppt. Lesen **bool**.

```cpp
virtual bool Aspose::Slides::Animation::IEffect::get_StopPreviousSound()=0
```

## Hinweise



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Rufe den ersten Effekt der ersten Folie ab.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Rufe den ersten Effekt der zweiten Folie ab.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Ändere den zweiten Effekt Enhancements/Sound auf "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Siehe auch

* Klasse [IEffect](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)