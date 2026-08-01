---
title: set_RepeatUntilNextClick()
second_title: Aspose.Slides voor C++ API-referentie
description: Dit attribuut geeft aan of het effect zich herhaalt tot de volgende klik. Schrijf bool.
type: docs
weight: 170
url: /nl/aspose.slides.animation/timing/set_repeatuntilnextclick/
---
## Timing::set_RepeatUntilNextClick(bool) methode


Dit attribuut geeft aan of het effect zich herhaalt tot de volgende klik. Schrijf **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilNextClick(bool value) override
```

## Opmerkingen



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Zie ook

* Klasse [Timing](../)
* Naamruimte [Aspose::Slides::Animation](../../)
* Bibliotheek [Aspose.Slides](../../../)