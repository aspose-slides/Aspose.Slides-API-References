---
title: set_Rewind()
second_title: Aspose.Slides voor C++ API-referentie
description: Dit attribuut geeft aan of het effect terugspoelt wanneer het afspelen is voltooid. Schrijf bool.
type: docs
weight: 326
url: /nl/aspose.slides.animation/itiming/set_rewind/
---
## ITiming::set_Rewind(bool) methode


Dit attribuut geeft aan of het effect terugspoelt wanneer het afspelen is voltooid. Schrijf **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_Rewind(bool value)=0
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

* Klasse [ITiming](../)
* Naamruimte [Aspose::Slides::Animation](../../)
* Bibliotheek [Aspose.Slides](../../../)