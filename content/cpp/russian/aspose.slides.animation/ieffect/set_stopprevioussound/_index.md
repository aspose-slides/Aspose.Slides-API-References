---
title: set_StopPreviousSound()
second_title: Aspose.Slides для C++ справка по API
description: Этот атрибут указывает, останавливает ли эффект анимации предыдущий звук. Записывается bool.
type: docs
weight: 209
url: /ru/aspose.slides.animation/ieffect/set_stopprevioussound/
---
## IEffect::set_StopPreviousSound(bool) метод


Этот атрибут указывает, останавливает ли эффект анимации предыдущий звук. Записывается **bool**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_StopPreviousSound(bool value)=0
```

## Примечания



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Get the first effect of the second slide.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Изменить звук второго эффекта Enhancements/Sound на "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Смотрите также

* Класс [IEffect](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)