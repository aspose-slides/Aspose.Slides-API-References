---
title: set_StopPreviousSound()
second_title: Aspose.Slides для C++ справочник API
description: Этот атрибут указывает, останавливает ли анимационный эффект предыдущее звучание. Запишите bool.
type: docs
weight: 209
url: /ru/aspose.slides.animation/effect/set_stopprevioussound/
---
## Effect::set_StopPreviousSound(bool) метод


Этот атрибут указывает, останавливает ли анимационный эффект предыдущее звучание. Запишите **bool**.

```cpp
void Aspose::Slides::Animation::Effect::set_StopPreviousSound(bool value) override
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
    // Изменить второй эффект Enhancements/Sound на "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## См. также

* Класс [Effect](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)