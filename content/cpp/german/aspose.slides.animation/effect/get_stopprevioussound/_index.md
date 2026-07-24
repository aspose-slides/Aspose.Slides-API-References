---
title: get_StopPreviousSound()
second_title: Aspose.Slides für C++ API Referenz
description: Dieses Attribut gibt an, ob der Animationseffekt den vorherigen Sound stoppt. Lesen **bool**.
type: docs
weight: 196
url: /de/aspose.slides.animation/effect/get_stopprevioussound/
---
## Effect::get_StopPreviousSound() Methode

Dieses Attribut gibt an, ob der Animationseffekt den vorherigen Sound stoppt. Lesen **bool**.

```cpp
bool Aspose::Slides::Animation::Effect::get_StopPreviousSound() override
```

## Anmerkungen

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Hole den ersten Effekt der ersten Folie.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Hole den ersten Effekt der zweiten Folie.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Ändere das Sound-Enhancement des zweiten Effekts zu "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Siehe auch

* Klasse [Effect](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)