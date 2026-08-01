---
title: get_AfterAnimationType()
second_title: Aspose.Slides voor C++ API-referentie
description: Definieert een after animation type voor effect. Lees AfterAnimationType.
type: docs
weight: 222
url: /nl/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() methode


Definieert een after animation type voor effect. Lees [AfterAnimationType](../../afteranimationtype/).

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
```

## Opmerkingen



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Haal het eerste effect van de eerste dia op.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Wijzig het effect After animation naar "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Zie ook

* Enum [AfterAnimationType](../../afteranimationtype/)
* Klasse [Effect](../)
* Naamruimte [Aspose::Slides::Animation](../../)
* Bibliotheek [Aspose.Slides](../../../)