---
title: set_StopPreviousSound()
second_title: Aspose.Slides für C++ API-Referenz
description: Dieses Attribut gibt an, ob der Animationseffekt den vorherigen Sound stoppt. Schreiben bool.
type: docs
weight: 209
url: /de/aspose.slides.animation/ieffect/set_stopprevioussound/
---
## IEffect::set_StopPreviousSound(bool) Methode


Dieses Attribut gibt an, ob der Animationseffekt den vorherigen Sound stoppt. Schreiben **bool**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_StopPreviousSound(bool value)=0
```

## Hinweise



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Hole den ersten Effekt der ersten Folie.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Hole den ersten Effekt der zweiten Folie.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Ändere das zweite Effekt-Enhancements/Sound zu "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Siehe auch

* Klasse [IEffect](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)