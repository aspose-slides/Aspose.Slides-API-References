---
title: get_AdvanceAfter()
second_title: Aspose.Slides für C++ API-Referenz
description: Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. bool lesen.
type: docs
weight: 105
url: /de/aspose.slides.slideshow/slideshowtransition/get_advanceafter/
---
## SlideShowTransition::get_AdvanceAfter() Methode


Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. Lesen **bool**.

```cpp
bool Aspose::Slides::SlideShow::SlideShowTransition::get_AdvanceAfter() override
```

## Anmerkungen



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Hole den ersten Folienübergang
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Überprüfe, ob das Flag Advance Slide After gesetzt ist
if (slideTransition->get_AdvanceAfter())
{
    // Hole den Wert für die Advance Slide After-Zeit
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Siehe auch

* Klasse [SlideShowTransition](../)
* Namensraum [Aspose::Slides::SlideShow](../../)
* Library [Aspose.Slides](../../../)