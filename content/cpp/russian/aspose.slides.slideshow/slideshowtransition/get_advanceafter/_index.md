---
title: get_AdvanceAfter()
second_title: Aspose.Slides для C++ справочник API
description: Этот атрибут указывает, будет ли слайдшоу переходить к следующему слайду после определённого времени. Читает bool.
type: docs
weight: 105
url: /ru/aspose.slides.slideshow/slideshowtransition/get_advanceafter/
---
## SlideShowTransition::get_AdvanceAfter() метод

Этот атрибут указывает, будет ли слайдшоу переходить к следующему слайду после определённого времени. Читает **bool**.

```cpp
bool Aspose::Slides::SlideShow::SlideShowTransition::get_AdvanceAfter() override
```

## Примечание



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Получить переход первого слайда
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Проверить, установлен ли флаг Advance Slide After
if (slideTransition->get_AdvanceAfter())
{
    // Получить значение времени Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## См. также

* Класс [SlideShowTransition](../)
* Пространство имён [Aspose::Slides::SlideShow](../../)
* Библиотека [Aspose.Slides](../../../)