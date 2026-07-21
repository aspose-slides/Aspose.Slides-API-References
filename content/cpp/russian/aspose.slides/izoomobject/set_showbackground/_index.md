---
title: set_ShowBackground()
second_title: Справочник API Aspose.Slides для C++
description: "Устанавливает значение, указывающее, будет ли Zoom использовать фон целевого слайда. Запишите bool. Значение по умолчанию: true"
type: docs
weight: 66
url: /ru/aspose.slides/izoomobject/set_showbackground/
---
## IZoomObject::set_ShowBackground(bool) method


Устанавливает значение, указывающее, будет ли Zoom использовать фон целевого слайда. Запишите **bool**. Значение по умолчанию: true

```cpp
virtual void Aspose::Slides::IZoomObject::set_ShowBackground(bool value)=0
```

## Примечания


В примере показано удаление фона изображения объекта Zoom: 
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