---
title: set_TransitionDuration()
second_title: Aspose.Slides для C++ справочник API
description: "Устанавливает длительность перехода между Zoom и слайдом. Тип float. Значение по умолчанию: 1.0f"
type: docs
weight: 118
url: /ru/aspose.slides/zoomobject/set_transitionduration/
---
## ZoomObject::set_TransitionDuration(float) метод

Устанавливает длительность перехода между Zoom и слайдом. Тип: **float**. Значение по умолчанию: 1.0f

```cpp
void Aspose::Slides::ZoomObject::set_TransitionDuration(float value) override
```

## Примечание

Если не указано (TransitionDur = 0), будет использован переход целевого слайда и временные параметры, связанные с этим переходом.

пример демонстрирует изменение длительности перехода между Zoom и слайдом:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## См. также

* Класс [ZoomObject](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)