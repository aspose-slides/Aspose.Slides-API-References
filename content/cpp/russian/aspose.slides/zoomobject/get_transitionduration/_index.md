---
title: get_TransitionDuration()
second_title: Справочник API Aspose.Slides для C++
description: "Получает длительность перехода между Zoom и слайдом. Читает float. Значение по умолчанию: 1.0f"
type: docs
weight: 105
url: /ru/aspose.slides/zoomobject/get_transitionduration/
---
## ZoomObject::get_TransitionDuration() метод

Возвращает длительность перехода между Zoom и слайдом. Читает **float**. Значение по умолчанию: 1.0f

```cpp
float Aspose::Slides::ZoomObject::get_TransitionDuration() override
```

## Примечания

Если не указано (TransitionDur = 0), будет использоваться переход целевого слайда и тайминги, связанные с этим переходом.

Пример демонстрирует изменение длительности перехода между Zoom и слайдом:
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