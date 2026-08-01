---
title: set_Rewind()
second_title: Aspose.Slides voor C++ API-referentie
description: Dit attribuut specificeert of het effect wordt teruggespoeld wanneer het klaar is met afspelen. Schrijf bool.
type: docs
weight: 248
url: /nl/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(bool) methode

Dit attribuut specificeert of het effect wordt teruggespoeld wanneer het klaar is met afspelen. Schrijf **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_Rewind(bool value) override
```

## Opmerkingen

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## Zie ook

* Klasse [Timing](../)
* Naamruimte [Aspose::Slides::Animation](../../)
* Bibliotheek [Aspose.Slides](../../../)