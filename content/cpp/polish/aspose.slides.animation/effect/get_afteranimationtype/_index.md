---
title: get_AfterAnimationType()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Definiuje typ animacji po zakończeniu efektu. Przeczytaj AfterAnimationType.
type: docs
weight: 222
url: /pl/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() metoda

Definiuje typ animacji po zakończeniu efektu. Przeczytaj [AfterAnimationType](../../afteranimationtype/).

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
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

* Wyliczenie [AfterAnimationType](../../afteranimationtype/)
* Klasa [Effect](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)