---
title: set_AfterAnimationType()
second_title: Aspose.Slides для справочника API C++
description: Определяет тип анимации после эффекта. Запишите AfterAnimationType.
type: docs
weight: 235
url: /ru/aspose.slides.animation/ieffect/set_afteranimationtype/
---
## IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) метод


Определяет тип анимации после эффекта. Запишите [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value)=0
```

## Примечания



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation to "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## См. также

* Перечисление [AfterAnimationType](../../afteranimationtype/)
* Класс [IEffect](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)