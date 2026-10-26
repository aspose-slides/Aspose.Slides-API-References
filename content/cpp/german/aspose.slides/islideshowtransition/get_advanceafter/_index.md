---
title: get_AdvanceAfter()
second_title: Aspose.Slides für C++ API-Referenz
description: Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. Lese bool.
type: docs
weight: 105
url: /de/aspose.slides/islideshowtransition/get_advanceafter/
---
## ISlideShowTransition::get_AdvanceAfter() Methode

Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. Lese **bool**.

```cpp
virtual bool Aspose::Slides::ISlideShowTransition::get_AdvanceAfter()=0
```

## Hinweise

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Hole die erste Folien-Transition
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Überprüfe, ob das Flag Advance Slide After gesetzt ist
if (slideTransition->get_AdvanceAfter())
{
    // Hole den Wert der Advance Slide After Time
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Siehe auch

* Klasse [ISlideShowTransition](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)