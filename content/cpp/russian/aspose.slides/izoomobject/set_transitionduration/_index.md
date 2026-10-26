---
title: set_TransitionDuration()
second_title: Aspose.Slides для C++ Справочник API
description: "Устанавливает продолжительность перехода между Zoom и слайдом. Запишите float. Значение по умолчанию: 1.0f"
type: docs
weight: 118
url: /ru/aspose.slides/izoomobject/set_transitionduration/
---
## IZoomObject::set_TransitionDuration(float) метод

Устанавливает продолжительность перехода между Zoom и слайдом. Запишите **float**. Значение по умолчанию: 1.0f

```cpp
virtual void Aspose::Slides::IZoomObject::set_TransitionDuration(float value)=0
```

## Примечания

Если не указано (TransitionDur = 0), будет использовать переход целевого слайда и связанные с ним тайминги. 

пример демонстрирует изменение продолжительности перехода между Zoom и слайдом: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## См. также

* Класс [IZoomObject](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)