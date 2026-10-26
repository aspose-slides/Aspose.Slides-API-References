---
title: get_AfterAnimationType()
second_title: Aspose.Slides voor C++ API-referentie
description: Definieert een after-animatietype voor effect. Lees AfterAnimationType.
type: docs
weight: 222
url: /nl/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() methode


Definieert een after-animatietype voor effect. Lees [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## Opmerkingen



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Haal het eerste effect van de eerste dia op.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Verander de After-animatie van het effect naar "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Zie ook

* Enum [AfterAnimationType](../../afteranimationtype/)
* Klasse [IEffect](../)
* Naamruimte [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)