---
title: set_TargetSlide()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает объект слайда, к которому привязан объект Slide Zoom. Запишите ISlide.
type: docs
weight: 14
url: /ru/aspose.slides/zoomframe/set_targetslide/
---
## ZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) метод

Устанавливает объект слайда, к которому привязан объект Zoom [Slide](../../slide/). Запишите [ISlide](../../islide/).

```cpp
void Aspose::Slides::ZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value) override
```

## Примечания

Следующий пример демонстрирует изменение целевого слайда и создание нового изображения для объекта Zoom [Slide](../../slide/):
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [ISlide](../../islide/)
* Класс [ZoomFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)