---
title: set_AdvanceAfter()
second_title: Aspose.Slides für C++ API-Referenz
description: Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. Schreiben Sie bool.
type: docs
weight: 118
url: /de/aspose.slides/islideshowtransition/set_advanceafter/
---
## ISlideShowTransition::set_AdvanceAfter(bool) Methode

Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. Schreiben Sie **bool**.

```cpp
virtual void Aspose::Slides::ISlideShowTransition::set_AdvanceAfter(bool value)=0
```

## Hinweise

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Holt den ersten Folienübergang
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Überprüft, ob das 'Advance Slide After'-Flag aktiviert ist
if (slideTransition->get_AdvanceAfter())
{
    // Holt den Wert für die Zeit bis zum automatischen Folienwechsel
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Siehe auch

* Klasse [ISlideShowTransition](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)