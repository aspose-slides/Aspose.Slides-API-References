---
title: get_AfterAnimationType()
second_title: Справочник API Aspose.Slides для C++
description: Определяет тип последующей анимации для эффекта. См. AfterAnimationType.
type: docs
weight: 222
url: /ru/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() метод


Определяет тип последующей анимации для эффекта. См. [AfterAnimationType](../../afteranimationtype/).

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
```

## Примечания


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Получить первый эффект первого слайда.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Изменить тип последующей анимации эффекта на "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## См. также

* Перечисление [AfterAnimationType](../../afteranimationtype/)
* Класс [Effect](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)