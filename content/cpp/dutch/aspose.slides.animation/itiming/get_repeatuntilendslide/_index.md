---
title: get_RepeatUntilEndSlide()
second_title: Aspose.Slides voor C++ API-referentie
description: Dit attribuut geeft aan of het effect zich herhaalt tot het einde van de dia. Lees bool.
type: docs
weight: 131
url: /nl/aspose.slides.animation/itiming/get_repeatuntilendslide/
---
## ITiming::get_RepeatUntilEndSlide() methode


Dit attribuut geeft aan of het effect zich herhaalt tot het einde van de dia. Lezen **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilEndSlide()=0
```

## Opmerkingen



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Haalt de effectenreeks op voor de eerste dia
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Haalt het eerste effect van de hoofdreeks op.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Wijzigt de Timing/Herhaling van het effect naar "Tot het einde van de dia"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Zie ook

* Klasse [ITiming](../)
* Naamruimte [Aspose::Slides::Animation](../../)
* Bibliotheek [Aspose.Slides](../../../)