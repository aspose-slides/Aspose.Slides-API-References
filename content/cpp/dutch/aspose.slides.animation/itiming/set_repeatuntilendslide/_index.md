---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides voor C++ API Referentie
description: Dit attribuut geeft aan of het effect zich herhaalt tot het einde van de dia. Schrijf bool.
type: docs
weight: 144
url: /nl/aspose.slides.animation/itiming/set_repeatuntilendslide/
---
## ITiming::set_RepeatUntilEndSlide(bool) methode


Dit attribuut geeft aan of het effect zich herhaalt tot het einde van de dia. Schrijf **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilEndSlide(bool value)=0
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

* Klasse [ITiming](../)
* Naamruimte [Aspose::Slides::Animation](../../)
* Bibliotheek [Aspose.Slides](../../../)