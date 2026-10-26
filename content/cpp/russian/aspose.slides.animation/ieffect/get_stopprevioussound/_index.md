---
title: get_StopPreviousSound()
second_title: Справочник API Aspose.Slides для C++
description: Этот атрибут указывает, останавливает ли эффект анимации предыдущий звук. Чтение bool.
type: docs
weight: 196
url: /ru/aspose.slides.animation/ieffect/get_stopprevioussound/
---
## IEffect::get_StopPreviousSound() метод


Этот атрибут указывает, останавливает ли эффект анимации предыдущий звук. Чтение **bool**.

```cpp
virtual bool Aspose::Slides::Animation::IEffect::get_StopPreviousSound()=0
```

## Замечания



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Получить первый эффект первого слайда.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Получить первый эффект второго слайда.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Изменить свойство Enhancements/Sound второго эффекта на "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## См. также

* Класс [IEffect](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)