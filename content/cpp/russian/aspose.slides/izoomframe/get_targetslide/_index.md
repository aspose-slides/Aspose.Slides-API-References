---
title: get_TargetSlide()
second_title: Справочник API Aspose.Slides для C++
description: Получает объект слайда, на который ссылается объект Slide Zoom. Читайте ISlide.
type: docs
weight: 1
url: /ru/aspose.slides/izoomframe/get_targetslide/
---
## IZoomFrame::get_TargetSlide() метод


Получает объект слайда, на который ссылается объект Zoom [Slide](../../slide/). Читайте [ISlide](../../islide/).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::IZoomFrame::get_TargetSlide()=0
```

## Примечания


В следующем примере демонстрируется изменение целевого слайда и создание нового изображения для объекта Zoom [Slide](../../slide/): 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISlide](../../islide/)
* Класс [IZoomFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)