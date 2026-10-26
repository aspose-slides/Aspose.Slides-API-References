---
title: set_StopPreviousSound()
second_title: Aspose.Slides für C++ API Referenz
description: Dieses Attribut gibt an, ob der Animationseffekt den vorherigen Sound stoppt. Schreiben Sie bool.
type: docs
weight: 209
url: /de/aspose.slides.animation/effect/set_stopprevioussound/
---
## Effect::set_StopPreviousSound(bool) Methode


Dieses Attribut gibt an, ob der Animationseffekt den vorherigen Sound stoppt. Schreiben Sie **bool**.

```cpp
void Aspose::Slides::Animation::Effect::set_StopPreviousSound(bool value) override
```

## Hinweise



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Holt den ersten Effekt der ersten Folie.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Holt den ersten Effekt der zweiten Folie.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Ändert den zweiten Effekt Enhancements/Sound zu "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Siehe auch

* Klasse [Effect](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)