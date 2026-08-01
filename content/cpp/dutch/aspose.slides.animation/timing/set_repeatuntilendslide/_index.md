---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides voor C++ API-referentie
description: Dit attribuut specificeert of het effect zich zal herhalen tot het einde van de dia. Schrijf bool.
type: docs
weight: 144
url: /nl/aspose.slides.animation/timing/set_repeatuntilendslide/
---
## Timing::set_RepeatUntilEndSlide(bool) methode


Dit attribuut specificeert of het effect zich zal herhalen tot het einde van de dia. Schrijf **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilEndSlide(bool value) override
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
* Naamruimte [Aspose::Slides::Animation](../../)
* Bibliotheek [Aspose.Slides](../../../)