---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides voor C++ API-referentie
description: Dit attribuut geeft aan of het effect wordt herhaald tot de volgende klik. Lees bool.
type: docs
weight: 157
url: /nl/aspose.slides.animation/itiming/get_repeatuntilnextclick/
---
## ITiming::get_RepeatUntilNextClick() methode

This attribute specifies if the effect will repeat until the next click. Read **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilNextClick()=0
```

## Opmerkingen



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Haalt de effectensequentie op voor de eerste dia
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Haalt het eerste effect van de hoofdsequentie op.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Wijzigt effect Timing/Repeat naar "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Zie ook

* Klasse [ITiming](../)
* Naamruimte [Aspose::Slides::Animation](../../)
* Bibliotheek [Aspose.Slides](../../../)