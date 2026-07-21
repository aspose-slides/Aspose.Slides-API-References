---
title: set_AfterAnimationType()
second_title: Aspose.Slides для C++ API справка
description: Определяет тип последующей анимации для эффекта. Запишите AfterAnimationType.
type: docs
weight: 235
url: /ru/aspose.slides.animation/effect/set_afteranimationtype/
---
## Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) метод

Определяет тип последующей анимации для эффекта. Запишите [AfterAnimationType](../../afteranimationtype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value) override
```

## Примечания

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation to "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Смотрите также

* Перечисление [AfterAnimationType](../../afteranimationtype/)
* Класс [Effect](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)