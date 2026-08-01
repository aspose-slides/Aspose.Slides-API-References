---
title: set_AfterAnimationType()
second_title: Aspose.Slides voor C++ API-referentie
description: Definieert een after animation type voor het effect. Schrijf AfterAnimationType.
type: docs
weight: 235
url: /nl/aspose.slides.animation/ieffect/set_afteranimationtype/
---
## IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) methode


Definieert een after animation type voor het effect. Schrijf [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value)=0
```

## Opmerkingen



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Haal het eerste effect van de eerste dia op.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Verander de After animation van het effect naar "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Zie ook

* Enum [AfterAnimationType](../../afteranimationtype/)
* Klasse [IEffect](../)
* Naamruimte [Aspose::Slides::Animation](../../)
* Bibliotheek [Aspose.Slides](../../../)