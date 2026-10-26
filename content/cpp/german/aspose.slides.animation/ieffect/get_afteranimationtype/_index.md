---
title: get_AfterAnimationType()
second_title: Aspose.Slides für C++ API-Referenz
description: Definiert einen Nachanimations-Typ für den Effekt. Lesen Sie AfterAnimationType.
type: docs
weight: 222
url: /de/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() Methode


Definiert einen Nachanimations-Typ für den Effekt. Lesen Sie [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## Hinweise



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation to "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Siehe auch

* Enum [AfterAnimationType](../../afteranimationtype/)
* Klasse [IEffect](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)