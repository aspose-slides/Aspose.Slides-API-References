---
title: set_AfterAnimationType()
second_title: Aspose.Slides für C++ API-Referenz
description: Definiert einen Nachanimations-Typ für den Effekt. Schreiben Sie AfterAnimationType.
type: docs
weight: 235
url: /de/aspose.slides.animation/ieffect/set_afteranimationtype/
---
## IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) Methode

Definiert einen Nachanimations-Typ für den Effekt. Schreiben Sie [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value)=0
```

## Anmerkungen



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation to "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Siehe auch

* Aufzählung [AfterAnimationType](../../afteranimationtype/)
* Klasse [IEffect](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)