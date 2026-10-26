---
title: get_AdvanceAfter()
second_title: Aspose.Slides для C++: справочник API
description: Этот атрибут определяет, будет ли слайд-шоу переходить к следующему слайду после заданного времени. Чтение bool.
type: docs
weight: 105
url: /ru/aspose.slides/islideshowtransition/get_advanceafter/
---
## ISlideShowTransition::get_AdvanceAfter() метод


Этот атрибут определяет, будет ли слайд-шоу переходить к следующему слайду после заданного времени. Чтение **bool**.

```cpp
virtual bool Aspose::Slides::ISlideShowTransition::get_AdvanceAfter()=0
```

## Примечания



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Получить первый переход слайда
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Проверить, установлен ли флаг Advance Slide After
if (slideTransition->get_AdvanceAfter())
{
    // Получить значение времени Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## См. также

* Класс [ISlideShowTransition](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)