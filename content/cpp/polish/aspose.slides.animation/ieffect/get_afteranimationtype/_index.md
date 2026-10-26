---
title: get_AfterAnimationType()
second_title: Aspose.Slides dla C++ - Odniesienie API
description: Zdefiniowano typ animacji po dla efektu. Przeczytaj AfterAnimationType.
type: docs
weight: 222
url: /pl/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() metoda


Zdefiniowano typ animacji po dla efektu. Przeczytaj [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## Uwagi



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation to "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Zobacz także

* Enum [AfterAnimationType](../../afteranimationtype/)
* Klasa [IEffect](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)