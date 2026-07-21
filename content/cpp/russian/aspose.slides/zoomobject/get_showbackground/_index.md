---
title: get_ShowBackground()
second_title: Aspose.Slides для C++ справочник API
description: "Получает значение, указывающее, будет ли Zoom использовать фон целевого слайда. Читается bool. Значение по умолчанию: true"
type: docs
weight: 53
url: /ru/aspose.slides/zoomobject/get_showbackground/
---
## ZoomObject::get_ShowBackground() метод

Получает значение, указывающее, будет ли Zoom использовать фон целевого слайда. Читается **bool**. Значение по умолчанию: true

```cpp
bool Aspose::Slides::ZoomObject::get_ShowBackground() override
```

## Примечания

пример демонстрирует удаление фона изображения объекта Zoom: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Смотрите также

* Класс [ZoomObject](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)