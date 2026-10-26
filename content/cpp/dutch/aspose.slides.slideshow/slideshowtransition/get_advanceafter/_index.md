---
title: get_AdvanceAfter()
second_title: Aspose.Slides voor C++ API-referentie
description: Dit attribuut geeft aan of de diavoorstelling naar de volgende dia gaat na een bepaalde tijd. Lezen bool.
type: docs
weight: 105
url: /nl/aspose.slides.slideshow/slideshowtransition/get_advanceafter/
---
## SlideShowTransition::get_AdvanceAfter() methode


Dit attribuut geeft aan of de diavoorstelling naar de volgende dia gaat na een bepaalde tijd. Lezen **bool**.

```cpp
bool Aspose::Slides::SlideShow::SlideShowTransition::get_AdvanceAfter() override
```

## Opmerkingen



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Haal de eerste diaovergang op
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Controleer of de vlag Advance Slide After is ingeschakeld
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