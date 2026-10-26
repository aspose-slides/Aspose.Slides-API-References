---
title: set_AdvanceAfter()
second_title: Справочник API Aspose.Slides для C++
description: Этот атрибут указывает, будет ли презентация переходить к следующему слайду после определённого времени. Запишите bool.
type: docs
weight: 118
url: /ru/aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) метод


Этот атрибут указывает, будет ли презентация переходить к следующему слайду после определённого времени. Запишите **bool**.

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
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

* Класс [SlideShowTransition](../)
* Пространство имён [Aspose::Slides::SlideShow](../../)
* Библиотека [Aspose.Slides](../../../)