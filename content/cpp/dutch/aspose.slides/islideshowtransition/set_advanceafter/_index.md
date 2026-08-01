---
title: set_AdvanceAfter()
second_title: Aspose.Slides voor C++ API Referentie
description: Dit attribuut geeft aan of de diavoorstelling naar de volgende dia gaat na een bepaalde tijd. Schrijf bool.
type: docs
weight: 118
url: /nl/aspose.slides/islideshowtransition/set_advanceafter/
---
## ISlideShowTransition::set_AdvanceAfter(bool) methode

Dit attribuut geeft aan of de diavoorstelling naar de volgende dia gaat na een bepaalde tijd. Schrijf **bool**.

```cpp
virtual void Aspose::Slides::ISlideShowTransition::set_AdvanceAfter(bool value)=0
```

## Opmerkingen



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Haal de eerste diaovergang op
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Controleer of de Advance Slide After vlag is aangevinkt
if (slideTransition->get_AdvanceAfter())
{
    // Haal de Advance Slide After Time waarde op
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Zie ook

* Klasse [ISlideShowTransition](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)