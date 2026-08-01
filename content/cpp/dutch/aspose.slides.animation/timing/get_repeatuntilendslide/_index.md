---
title: get_RepeatUntilEndSlide()
second_title: Aspose.Slides voor C++ API-referentie
description: Dit attribuut geeft aan of het effect zal herhalen tot het einde van de dia. Lees bool.
type: docs
weight: 131
url: /nl/aspose.slides.animation/timing/get_repeatuntilendslide/
---
## Timing::get_RepeatUntilEndSlide() methode


Dit attribuut geeft aan of het effect zal herhalen tot het einde van de dia. Lees **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilEndSlide() override
```

## Opmerkingen



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Zie ook

* Klasse [Timing](../)
* Namespace [Aspose::Slides::Animation](../../)
* Bibliotheek [Aspose.Slides](../../../)