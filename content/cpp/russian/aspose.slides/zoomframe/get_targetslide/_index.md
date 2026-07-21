---
title: get_TargetSlide()
second_title: Справочник API Aspose.Slides для C++
description: Получает объект слайда, к которому привязан объект Slide Zoom. См. ISlide.
type: docs
weight: 1
url: /ru/aspose.slides/zoomframe/get_targetslide/
---
## ZoomFrame::get_TargetSlide() метод

Получает объект слайда, к которому привязан объект [Slide](../../slide/) Zoom. См. [ISlide](../../islide/).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::ZoomFrame::get_TargetSlide() override
```

## Примечания

Следующий пример демонстрирует изменение целевого слайда и создает новое изображение для объекта [Slide](../../slide/) Zoom:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISlide](../../islide/)
* Класс [ZoomFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)