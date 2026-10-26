---
title: set_AfterAnimationType()
second_title: Aspose.Slides dla interfejsu API C++
description: Definiuje typ animacji po zakończeniu efektu. Zapisz AfterAnimationType.
type: docs
weight: 235
url: /pl/aspose.slides.animation/effect/set_afteranimationtype/
---
## Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) metoda

Definiuje typ animacji po zakończeniu efektu. Zapisz [AfterAnimationType](../../afteranimationtype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value) override
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
* Klasa [Effect](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)