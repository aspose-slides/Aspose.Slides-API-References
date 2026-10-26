---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides voor C++ API-referentie
description: Dit attribuut geeft aan of het effect zich herhaalt tot de volgende klik. Lees bool.
type: docs
weight: 157
url: /nl/aspose.slides.animation/timing/get_repeatuntilnextclick/
---
## Timing::get_RepeatUntilNextClick() methode


Dit attribuut geeft aan of het effect zich herhaalt tot de volgende klik. Lees **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilNextClick() override
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