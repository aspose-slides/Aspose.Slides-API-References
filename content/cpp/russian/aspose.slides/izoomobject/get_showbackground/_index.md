---
title: get_ShowBackground()
second_title: Aspose.Slides для C++ Справка API
description: "Получает значение, указывающее, будет ли Zoom использовать фон целевого слайда. Чтение bool. Значение по умолчанию: true"
type: docs
weight: 53
url: /ru/aspose.slides/izoomobject/get_showbackground/
---
## IZoomObject::get_ShowBackground() метод


Получает значение, указывающее, будет ли Zoom использовать фон целевого слайда. Чтение **bool**. Значение по умолчанию: true

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ShowBackground()=0
```

## Примечания


В примере демонстрируется удаление фона изображения объекта Zoom: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## См. также

* Класс [IZoomObject](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)