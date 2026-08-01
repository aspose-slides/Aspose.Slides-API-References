---
title: get_Rewind()
second_title: Aspose.Slides voor C++ API-referentie
description: Dit attribuut geeft aan of het effect terugspoelt wanneer het afspelen is voltooid. Lezen bool.
type: docs
weight: 235
url: /nl/aspose.slides.animation/timing/get_rewind/
---
## Timing::get_Rewind() methode


Dit attribuut geeft aan of het effect terugspoelt wanneer het afspelen is voltooid. Lezen **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_Rewind() override
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