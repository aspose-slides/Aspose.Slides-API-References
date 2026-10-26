---
title: get_AdvanceAfter()
second_title: Aspose.Slides voor C++ API-referentie
description: Dit attribuut geeft aan of de diavoorstelling naar de volgende dia gaat na een bepaalde tijd. Lees bool.
type: docs
weight: 105
url: /nl/aspose.slides/islideshowtransition/get_advanceafter/
---
## ISlideShowTransition::get_AdvanceAfter() methode


Dit attribuut geeft aan of de diavoorstelling naar de volgende dia gaat na een bepaalde tijd. Lees **bool**.

```cpp
virtual bool Aspose::Slides::ISlideShowTransition::get_AdvanceAfter()=0
```

## Opmerkingen



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Haal de eerste diaovergang op
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Controleer of de Advance Slide After-vlag is aangevinkt
if (slideTransition->get_AdvanceAfter())
{
    // Haal de Advance Slide After-tijdwaarde op
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Zie ook

* Klasse [ISlideShowTransition](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)