---
title: set_AdvanceAfter()
second_title: Aspose.Slides для C++ справочника API
description: Этот атрибут указывает, будет ли показ слайдов переходить к следующему слайду после определённого времени. Запишите bool.
type: docs
weight: 118
url: /ru/aspose.slides/islideshowtransition/set_advanceafter/
---
## ISlideShowTransition::set_AdvanceAfter(bool) метод

Этот атрибут указывает, будет ли показ слайдов переходить к следующему слайду после определённого времени. Запишите **bool**.

```cpp
virtual void Aspose::Slides::ISlideShowTransition::set_AdvanceAfter(bool value)=0
```

## Примечания

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Получить первый переход слайда
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Проверить, установлен ли флаг Advance Slide After
if (slideTransition->get_AdvanceAfter())
{
    // Получить значение свойства Advance Slide After Time
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## См. также

* Класс [ISlideShowTransition](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)