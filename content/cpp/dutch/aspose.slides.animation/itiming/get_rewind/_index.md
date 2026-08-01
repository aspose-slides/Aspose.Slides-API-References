---
title: get_Rewind()
second_title: Aspose.Slides voor C++ API-referentie
description: Dit attribuut specificeert of het effect terugspoelt wanneer het afspelen is voltooid. Lezen bool.
type: docs
weight: 313
url: /nl/aspose.slides.animation/itiming/get_rewind/
---
## ITiming::get_Rewind() methode

Dit attribuut specificeert of het effect terugspoelt wanneer het afspelen is voltooid. Lezen **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_Rewind()=0
```

## Opmerkingen


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Haal de effectensequentie op voor de eerste dia
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Haal het eerste effect van de hoofdsequentie op.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Schakel de effect Timing/Rewind in.
effect->get_Timing()->set_Rewind(true);
```

## Zie ook

* Klasse [ITiming](../)
* Naamruimte [Aspose::Slides::Animation](../../)
* Bibliotheek [Aspose.Slides](../../../)