---
title: get_StopPreviousSound()
second_title: Aspose.Slides для C++ справочник API
description: Этот атрибут указывает, останавливает ли анимационный эффект предыдущий звук. Читать bool.
type: docs
weight: 196
url: /ru/aspose.slides.animation/effect/get_stopprevioussound/
---
## Effect::get_StopPreviousSound() метод


Этот атрибут указывает, останавливает ли анимационный эффект предыдущий звук. Читать **bool**.

```cpp
bool Aspose::Slides::Animation::Effect::get_StopPreviousSound() override
```

## Примечания



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Получить первый эффект первого слайда.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Получить первый эффект второго слайда.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Изменить звук второго эффекта (Enhancements/Sound) на "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## См. также

* Класс [Effect](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)