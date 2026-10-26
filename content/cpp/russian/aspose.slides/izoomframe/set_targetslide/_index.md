---
title: set_TargetSlide()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает объект слайда, на который ссылается объект Slide Zoom. Записывает ISlide.
type: docs
weight: 14
url: /ru/aspose.slides/izoomframe/set_targetslide/
---
## IZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) метод

Устанавливает объект слайда, на который ссылается объект Zoom [Slide](../../slide/). Записывает [ISlide](../../islide/).

```cpp
virtual void Aspose::Slides::IZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value)=0
```

## Примечания

Следующий пример демонстрирует изменение целевого слайда и создание нового изображения для объекта Zoom [Slide](../../slide/):
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISlide](../../islide/)
* Класс [IZoomFrame](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)