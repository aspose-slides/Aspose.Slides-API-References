---
title: set_ShowBackground()
second_title: Справочник API Aspose.Slides для C++
description: "Устанавливает значение, которое определяет, будет ли Zoom использовать фон целевого слайда. Записывается bool. Значение по умолчанию: true"
type: docs
weight: 66
url: /ru/aspose.slides/zoomobject/set_showbackground/
---
## ZoomObject::set_ShowBackground(bool) метод

Устанавливает значение, которое указывает, будет ли Zoom использовать фон целевого слайда. Запишите **bool**. Значение по умолчанию: true

```cpp
void Aspose::Slides::ZoomObject::set_ShowBackground(bool value) override
```

## Примечания

Пример демонстрирует удаление фона изображения объекта Zoom:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## См. также

* Класс [ZoomObject](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)