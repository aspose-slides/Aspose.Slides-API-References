---
title: set_RepeatUntilNextClick()
second_title: Aspose.Slides voor C++ API-referentie
description: Dit attribuut specificeert of het effect zich zal herhalen tot de volgende klik. Schrijf bool.
type: docs
weight: 170
url: /nl/aspose.slides.animation/itiming/set_repeatuntilnextclick/
---
## ITiming::set_RepeatUntilNextClick(bool) methode


Dit attribuut specificeert of het effect zich zal herhalen tot de volgende klik. Schrijf **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilNextClick(bool value)=0
```

## Opmerkingen



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Haalt de effectensequentie op voor de eerste dia
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Haalt het eerste effect van de hoofdsequentie op.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Wijzigt effect Timing/Repeat naar "Tot einde van dia"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Zie ook

* Klasse [ITiming](../)
* Namespace [Aspose::Slides::Animation](../../)
* Bibliotheek [Aspose.Slides](../../../)