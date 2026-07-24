---
title: set_AdvanceAfter()
second_title: Aspose.Slides für C++ API-Referenz
description: Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. Schreiben Sie bool.
type: docs
weight: 118
url: /de/aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) Methode

Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. Schreiben Sie **bool**.

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
```

## Anmerkungen


```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Hole den ersten Folienübergang
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Prüfe, ob das Flag 'Advance Slide After' gesetzt ist
if (slideTransition->get_AdvanceAfter())
{
    // Hole den Wert der 'Advance Slide After'-Zeit
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Siehe auch

* Klasse [SlideShowTransition](../)
* Namensraum [Aspose::Slides::SlideShow](../../)
* Bibliothek [Aspose.Slides](../../../)