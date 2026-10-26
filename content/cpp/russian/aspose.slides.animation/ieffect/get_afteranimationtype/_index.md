---
title: get_AfterAnimationType()
second_title: Справочник API Aspose.Slides для C++
description: Определён тип анимации после эффекта. См. AfterAnimationType.
type: docs
weight: 222
url: /ru/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() метод


Определён тип анимации после эффекта. См. [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## Замечания



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation to "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## См. также

* Enum [AfterAnimationType](../../afteranimationtype/)
* Класс [IEffect](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)