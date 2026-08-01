---
title: set_AdvanceAfter()
second_title: Aspose.Slides voor C++ API-referentie
description: Dit attribuut geeft aan of de diavoorstelling naar de volgende dia gaat na een bepaalde tijd. Schrijf bool.
type: docs
weight: 118
url: /nl/aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) methode


Dit attribuut geeft aan of de diavoorstelling naar de volgende dia gaat na een bepaalde tijd. Schrijf **bool**.

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
```

## Opmerkingen



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Haal de eerste dia-transitie op
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Controleer of de vlag Advance Slide After is aangevinkt
if (slideTransition->get_AdvanceAfter())
{
    // Haal de waarde van Advance Slide After Time op
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Zie ook

* Klasse [SlideShowTransition](../)
* Naamruimte [Aspose::Slides::SlideShow](../../)
* Bibliotheek [Aspose.Slides](../../../)